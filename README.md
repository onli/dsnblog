A basic, pre-alpha implementation of a distributed social network blog system.

The aim is to have a blog system which supports all the basics of a
normal blog, but adding functionality which is common in social 
networks, like adding friends, listing them and writing them a message.

The blog itself shall have some special capabilities, especially pure
frontend-administration and a complete caching of all pages.

Using Open Social as the target-api, plugins for other blog engines like
wordpress could enable them to be a part of the network as well.

Created as an assessed assignment for the lecture [Security in Online Social Networks](http://www.uni-siegen.de/fb5/itsec/lehre/ss12/sec-osn-ss12/index.html), Siegen, summer semester 2012.

Using ruby, sinatra, browserid.

Dependencies

 * General:
  * ruby
  * libxml2-dev (used by sanitize) 
  * libxslt1-dev (used by sanitize)
  * libgsl-ruby1.9.1 (used by classifier, or install the gem gsl. optional)

 * gems:
  * sinatra
  * sinatra-browserid (the one in the repo is currently defunct, see http://40hourworkweek.blogspot.de/2012/06/i-have-been-playing-with-mozillas.html for a solution)
  * json
  * sqlite3
  * sanitize
  * nokogiri
  * mechanize
  * madeleine
  * pony 
  * htmlentities
  * classifier
  * RedCloth

