# adoption.rubygems.org

<b>Name of the Project Mentor:</b> Nick Quaranto, Benjamin Fleischer

<b>Name of the Project Team:</b> Angela Guette, Lina Torres

<b>Name of the Project:</b> RubyGems.org Adoption Center</br>

<b>URL:</b> https://rubygems.org</br>


<b>About the Project:</b>

RubyGems needs a way to mark a gem as "maintainer needed" or "someone please take this gem over". This project would drive the creation of an "Adoption Center" (Possibly at http://adoption.rubygems.org) where people could list gems that want a maintainer/someone new to help fix issues, cut releases, etc, and then assist in the handoff of the gem.

Some more background and required reading on this:

https://groups.google.com/forum/#!msg/rubygems-org/niS5ZO9DNgk/5Fhg9Q3QR7YJ
http://www.benjaminfleischer.com/2014/08/17/rubygems-adoption-center/
https://github.com/rubygems/rubygems.org/issues/725


<b>Project Plan:</b>

* Create a new web UI for the adoption of gems with the framework rails
* This app must be connected with the rubygems.org API for manage the sessions of the users and the gems
* Advertise when a gem is looking for owners: When the gem owner sets 'looking for maintainers' to be true then an 'adoption' record is associated with the gem which also includes the user's id and the date. When a gem has an associated adoption record then the gem's page will show that it is 'up for adoption' and there will be an interface for an authenticated rubygems.org user to make an 'adoption request'
* When a gem is 'up for adoption' then it can be found via search of some sort and/or listed on an 'up for adoption' page Whether or not the searching/viewing user is logged in or not. This may be a separate app that pulls in data over the rubygems.org API
* Creating a gem ownership request: When an adoption request is made then the gem owners are notified of it and they may respond either via email, rubygems.org, or a gem command
* Approving a gem ownership request: When an adoption request is approved then the requestor is added as an owner and the requestor is notified and the gem's adoption record status is set to 'no longer up for adoption' (other requests may still be outstanding)
* Rejecting a gem ownership request: When an adoption request is denied then the requestor is notified, preferably with a nice message
* A gem owner may generate a badge to place in the gem's repository, linking to rubygems.org: probably also add copy about this process to RubyGems guide somewhere and under the RubyGems GitHub org.
