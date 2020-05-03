---
layout: page
title: Sprint 4 Achievements
---


## Professional Achievements 
-----

Adding do commits for adding a migration and adding one line of code which was to do with the migration and then committing. so i committed with only one file added and one line of code which makes it easy to see what i have done for that job.[Here](https://github.com/SoftEnOP/op-stats-team-1/commit/76389ce166e7814ffb0c1ae0017159f4730280fe) is the commit.

A team mate checked the banning of the user and when banning them they were not being banned by one week so i looked into the database and found that it was adding a date that had already been so this was not banning anyone. [Here](https://github.com/SoftEnOP/op-stats-team-1/commit/8b7cb3ac1e59d7c6d343a33afcc4449bf149a19b) is the fix one line of code changed to add a week after doing some research online to find out how to do this, as well as changing null to Nullable for unbanning the user that the user that had banned them would still show up.

Thanks to my team mate Ethan for finding out why my unbanning user method would not change in the database, I was missing the brackets for the save method. [Here](https://github.com/SoftEnOP/op-stats-team-1/commit/6b93fac0803d66513a27a31639e98b39891edaf0#diff-061119edc20ed22279af13ba89ddc82aR91) is the commit.


## Technical Achievements
------

We had another migration issue as the userTable and groups table primary id key's were set to unsigned big integer when they should have been set to big increments and this fixed our migration. [Here](https://github.com/SoftEnOP/op-stats-team-1/commit/bb4ca453e88eac6647e1eafd83552c3050ec1905) is the commit.

Unbanning was my task for the sprint
I also added a blocked_by to the user model so i could then add the user id of the person that had block them so that they were the ones that could unblock them as this is what the client wanted.

I added 2 methods to the home controller for banned users and unbanning of a user.

I added a page to see the users that i had banned so i could un ban them added a link to the navbar to get to this page and get route for this page and a post route to tel the database what person you want to unban.
[Here](https://github.com/SoftEnOP/op-stats-team-1/commit/d05aa7dbf4599c138148a8d39915b85d927215fd) is the commit 

And a merge of the listing-Scores branch [here](https://github.com/SoftEnOP/op-stats-team-1/commit/45362a1467ae9d878dad462f34e58ee31c8a1b2e).



