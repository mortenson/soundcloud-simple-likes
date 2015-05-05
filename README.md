# Soundcloud Simple Likes (Favorites)

I use Soundcloud a bit and have over 500 likes that are unsearchable, unsortable, and unshuffalable using the website. This got pretty frustrating, so I peeked into the API and created a simple script that loads up the current authenticated user's likes and displays them using ListJS, which handles all the complexities of sorting and searching for me. 

Here's what it looks like:

![screenshot](http://i.imgur.com/w9DAopo.png)

# Installation instructions

1. Register a new App at http://soundcloud.com/you/apps
1. Clone the repository to a random folder or into your webroot.
1. Edit soundcloud.html and enter your App's Client ID under the `SC.initialize()` call.
1. Visit soundcloud.html and authenticate using your credentials.
1. Enjoy!

# Legal stuff

The purpose of this codebase is to be a simple example of using the Soundcloud JavaScript SDK, as well as being useful to users who are looking for a stupid-simple Soundcloud interface for sorting their likes. 

**Use this codebase at your own risk.** By entering your App's Client ID you should accept any consequences that may come as a result of using this code to stream your likes from Soundcloud.

Although this is not associated with a specific product/app, I have read through https://developers.soundcloud.com/docs/api/terms-of-use and do not believe that this is in any violation of Soundcloud's terms of use. I am in no way competing with their product and have purposefully limited the functionality of this script so that users are encouraged to continue using the primary site.
