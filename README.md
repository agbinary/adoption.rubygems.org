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

1. Create a new web UI for the adoption of gems with the framework rails
2. Make the homepage with a list with gems for adoption and a searcher
3. Develop the functionality and make the view for make a request of adoption
4. Develop the functionality and make the view for up the adoption of a gem
5. Develop an authentication view
6. Develop a gems view
7. Make the connection with the rubygems.org API for manage the sessions of the users and the gems
8. When a gem is up for adoption make the record of the adoption and change the status on the views
9. Develop the function of send e-mails for notify the requesters and maintainers
10. When a request save the records and send notification to the actual maintainer
11. Develop and admin page to the actual maintainer for accept request of possible adoptants
12. When a requestor is accepted change the status of the gem
13. Notify to the adoptants his responses 
14. Make a badge in the github repo linking to the site of the adoption
15. Make the documentation of the app


![Diagrama](https://slack-files.com/files-tmb/T03DP9847-F04D28AAK-3fba283415/adoptionrubygems_org__1__1024.png)
