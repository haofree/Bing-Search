bing-search: Use Bing from the command line
===========================================

**Bing-search** allows you to use Bring from the comfort of your shell.

usage: bing-search [-h] [-i] [-s] [-r] [-n] <Search Terms>

Run searches using Bing

optional arguments:
  -h, --help  show this help message and exit
  -i          search images
  -s          search spelling
  -r          search related
  -n          search news

Examples
--------
*Some of the results in the examples were omitted for brevity*

Regular Search: ::

  $ bing-search reddit
  reddit: the front page of the internet
  use the following search parameters to narrow your results: reddit:{name} find things posted in {name} only author:{username} return things submitted by {username} only
  http://www.reddit.com/

  Pictures and Images
  reddit: the front page of the internet ... use the following search parameters to narrow your results: reddit:{name}
  http://www.reddit.com/r/pics/

  funny
  reddit: the front page of the internet ... use the following search parameters to narrow your results: reddit:{name}
  http://www.reddit.com/r/funny/

Image Search: ::
  
  $ bing-search -i lolcat
  Lolcat 1905 Demotivational Poster Demotivational Posters Daily ...
  http://1.bp.blogspot.com/_3IjRgoGWUBo/SetWkdH-tSI/AAAAAAAAAHw/QqPrmWDqCPU/s400/lolcat-1905.jpg
  Size: 22969
  Dimensions: 320x400

  LOLcat Friday: Internet Edition
  http://iamkio.files.wordpress.com/2011/04/lolcat-wikipedia-editing.jpg
  Size: 63711
  Dimensions: 750x600

  ... tutorial will walk you through the steps of creating a LOLCAT
  http://mintyferret.com/wp-content/uploads/2007/07/lolcat7.gif
  Size: 89222
  Dimensions: 420x349

  http://piccsy.com/2011/04/lolcat/
  http://images.piccsy.com/cache/images/lolcat-79890-500-658.jpg
  Size: 83255
  Dimensions: 500x658

News Search: ::

  $ bing-search -n hacker news
  Investors in Murdoch's News Corp forgive hacking
  http://www.msnbc.msn.com/id/43565537

  Leveson Inquiry: Hacking scandal a 'wake-up call'
  http://www.independent.co.uk/news/media/press/leveson-inquiry-hacking-scandal-a-wakeup-call-6287535.html

  U.K. watchdog arrests ex-police officer in bribery, phone hacking probe
  http://www.thestar.com/news/world/article/1113319--u-k-watchdog-arrests-ex-police-officer-in-bribery-phone-hacking-probe

  Hackers apparently target STRATFOR again
  http://www.policeone.com/communications/articles/4928402-Hackers-apparently-target-STRATFOR-again/

  Cameron will attend hacking inquiry if asked: Downing St
  http://www.asiaone.com/News/Latest%2BNews/World/Story/A1Story20120110-320862.html

Related Search: ::
  
  $ bing-search -r Rick Astley
  Rick Astley Death
  http://www.bing.com/search?q=Rick+Astley+Death

  Rick Astley Music
  http://www.bing.com/search?q=Rick+Astley+Music

  Rick Astley Video
  http://www.bing.com/search?q=Rick+Astley+Video

  Rick Astley Songs
  http://www.bing.com/search?q=Rick+Astley+Songs

  Rick Astley Photos
  http://www.bing.com/search?q=Rick+Astley+Photos

  Rick Astley Biography
  http://www.bing.com/search?q=Rick+Astley+Biography

  Rick Astley Music Video
  http://www.bing.com/search?q=Rick+Astley+Music+Video

  Rick Rolled
  http://www.bing.com/search?q=Rick+Rolled

Dependencies
------------
  This couldn't have been done without `pybing`_

.. _`pybing`: http://code.google.com/p/pybing
