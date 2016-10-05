# Driven Stream

This is a Jekyll/Bootstrap backed blog with a Disqus comment engine. It is published to:

http://stream.drivenalliance.com/


## Contributing

If you are a part of Driven or an Associate and would like to make a post, do the following (TLDR: clone the repo and duplicate the layout of one of the existing files in /_post)...

### Non-technical people
Write your post/article and email it to stream@drivenalliance.com. Any format is fine. The person watching that mailbox will post it on the site and email you back a confirmation (may take a day or so).

### People with the technical skills (git/jekyll)
#### Adding a new post
* Clone a local copy of https://github.com/DrivenAllianceStream/drivenalliancestream.github.io
* Switch to the develop branch
* Make a dupicate of any post (e.g. _posts/2014-10-17-problems.md), rename it with the current date and your post title (eg 2014-12-09-MyPost.md)
* Open the file in a markdown editor (Mou on OSX is great http://25.io/mou/), or a plain text editor
* Change the title, category, tagline, author, tags to anything you need to
* Write your post in below {% include JB/setup %} 
* [Run the jekyll server locally](https://jekyllrb.com/docs/installation/) to view your post and make sure it's all good
* Commit back to the develop branch

#### Publishing your post
* Make a backup copy of the _site folder that jekyll creates
* Switch to master, delete all the files and copy in the contents of your _site backup folder (from a previous step)
* Commit on master 
* Push master and develop back to github

If you don't have permission to push to the repo contact @kevint

## Jekyllbootstrap

For all usage and documentation of the underlying engine please see: <http://jekyllbootstrap.com>
