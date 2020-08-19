feeds
=====
The feeds project can be found at https://www.drupal.org/project/feeds

Here you may find several changes that I made to the original project on Drupal.org.

Under the Feeds/libraries folder you will find common_syndication_parser.inc. 

The code was changed there to account for the dc_source field. 

Under Feeds_Imagegrabber you will find multiple code changes to account for different feed sources such as 
Scoop.it, 
BoingBoing, 
Feedburner, 
Tumblr.com, 
Youtube, 
Vimeo. 

Regular expressions are used by preg_match to find the intended content. 

Ideally the changes made in the parser should be in its own custom parser and a plugin.
