# Google Enhanced Ecommerce for Magento
The official extension for adding Google Universal Analytics and Enhanced Ecommerce to your Magento store.


In case you've missed their announcements, Google has been making huge strides when it comes to analyzing eCommerce data with its relatively recent [Universal Analytics](https://support.google.com/analytics/answer/2790010?hl=en) upgrade and most recently with [Enhanced Ecommerce](https://support.google.com/analytics/answer/6014841?hl=en).

By reading the Google posts from the hyperlinks above or any of the numerous articles available online, you should quickly and easily reach the conclusion that if you are in the business of selling merchandise online, you want this.

However, properly setting up your Magento site to take advantage of these offerings isn’t quick or easy, and that’s why Blue Acorn is proud to have been [chosen by our partners at Google](http://analytics.blogspot.com/2014/11/brian-gavin-diamonds-sees-60-increase.html) to build the official Magento extension that will make this integration a far more pleasant one.

**Please note** that simply downloading this extension does not automatically generate an account with Google, set up your username and password, and send you your favorite latte via a Google drone (although that would be cool).

You’ll still need to register with Google, which you can do by clicking [here](https://support.google.com/analytics/answer/1008015).

If you already have the classic version of Google Analytics (ga.js), you will need to upgrade to Universal Analytics **BEFORE** downloading this extension in order to have data continuity. You can find information on how to do that by clicking [here](https://developers.google.com/analytics/devguides/collection/upgrade/).

If you're lucky enough to be building out a clean slate implementation of Magento and you have not yet installed any analytics scripts, just go ahead and install this extension, then smile.

Please [email SOZO Design](mailto:clive:sozodesign.co.uk) with any support questions you may have or visit the [Github page](http://github.com/clivewalkden/UniversalAnalytics).

Changelog
---------

**V0.5.5 - 8/23/2017**
- Minor bugfixes
- Added sample size and made it admin controlled

**V0.5.4 - 3/19/2014**
- Minor bugfixes
- Added a composer file for the module
- Changed private methods in Monitor class to protected
- Fixed some issues with going backwards and forwards in the checkout process
- Added a default listname for collection classes that would otherwise not parse out a listname
- Added this handy readme file

**V0.5.3 - 2/25/2015**
- Made a new GitHub repository page at: http://github.com/BlueAcornInc/UniversalAnalytics
- Validate supplied currency code against list supplied by Google (uses USD by default)
- Added additional method documentation in various classes
