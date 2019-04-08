# README

The first of the 3 ruby on rails projects for HackUMass training,
This is also the result of episode one of the "12 Web Apps in 12 Weeks" of Mackenzie Child's Ruby on Rails series https://youtu.be/7-1HCWbu7iU

* Ruby version
ruby-2.5.3

This web app is meant to be similar for an online forum like reddit, which is appropirately named as raddit.

This will be filled in as I follow along with the video

The functionality are as follows

+ link creation, revision, and deletion
  * Users who have signed in are able to create posts in the form of links
  * Users who have created the link are able to modify/delete the posts when clicked on the link
  * Any account will be able to view and visit a link, but will not be able to vote, create posts, or modify data

+ Forum interation
  * Signed in users can be able to updoot or downdoots posts and the cummulative total can be seen by all vistors of the site

+ Security
  * Users that have created the link are the only one that can view then modify/destroy that they have created.
  * Only authorized accounts can access paths of the webpage that manipulate the data of the links
  * Only those signed in are allowed to upvote or downvote a link

* Deployment instructions
It has beeon only tested on the local server, but you are welcome to try to deploy it!
to run the development server on a computer with a ruby on rails environment installed run this command,

```
rails server
```

##

