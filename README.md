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
2. Make the homepage view with a list with gems for adoption and a searcher
3. Develop the functionality and make the view for make a request of adoption
4. Develop the functionality and make the view for up the adoption of a gem
5. Develop an authentication view
6. Make the connection with the rubygems.org API for manage the sessions of the users and the gems
7. When a gem is up for adoption make the record of the adoption and change the status on the views
8. Develop the function of send e-mails for notify the requesters and maintainers
9. When a request save the records and send notification to the actual maintainer
10. Develop and admin page to the actual maintainer for accept request of possible adoptants
11. When a requestor is accepted change the status of the gem
12. Notify to the adoptants his responses 
13. Make a badge in the github repo linking to the site of the adoption
14. Make the documentation of the app


<b>Timeline:</b>


            LOGIC
            
<b>Gems</b>

List gems available for adoption ___                  2 days

Order gem list by criteria (Recent, older) ___       2 days

Filter gems by search criteria (Name) ___            3 days

Show gem information ___                             2 days

<b>Users</b>

Login and logout (Using RubyGems API) ___            2 weeks

List user gems ___                                   2 days

Mark/Unmark a gem for adoption ___                   3 days

List adoption requests ___                           2 days

Accept/reject gem adoption request ___               3 days

Send adoption request ___                            2 days

Notify by email of a new adoption request ___        1 week

Notify by email the adoption request status   

(accepted  or rejected)

            VIEWS
Landing page ___                                     1 week

Search page ___                                      1 week

Gem page ___                                         4 days

Login page ___                                       3 days

User dashboard ___                                   1 week

            OTHER
            
Deploy to Heroku ___                                 1 week

Write documentation ___                              1 week


![Diagrama](https://slack-files.com/files-tmb/T03DP9847-F04D28AAK-3fba283415/adoptionrubygems_org__1__1024.png)
