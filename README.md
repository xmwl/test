Hello!

You need to spin up a local web server to preview the HTML pages (the pictures won't show up otherwise).

Here's how:

  python -m SimpleHTTPServer 4567
  open http://0.0.0.0:4567


The CSS is organized based on the principles of Immutable CSS. Here are a few great reads that details the philosophy behind it.

  What is Immutable CSS? http://firedev.com/posts/2015/immutable-css/
  CSS and Scalability by Adam Morse (author of the Tachyons framework) -- http://mrmrs.io/writing/2016/03/24/scalable-css/
  Kiss My Classname: A Counterpoint by John Polacek -- https://medium.com/@johnpolacek/kiss-my-classname-a-counterpoint-3ca41f0aed1a
  The Journey of Simplifying our CSS by the folks at DNSimple -- https://blog.dnsimple.com/2017/01/CSS-journey/

The naming conventions are adapted from Tachyons CSS (tachyons.io). If you have trouble following the generated CSS,
please spend some time playing with Tachyons to get a hang of it.


