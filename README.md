LimeLightCRMAPI
===============

PHP integration with True Marketing Partner's Lime Light API

***UNOFFICIAL***

I got tired of rewriting this code over and over again, so I built these classes and now I don't have to keep rewriting. The help information is freely available.

This is a beta, I'm in the process of testing as I put it up. There are companies that will integrate for you, but if you're familiar with PHP and MySQL you can implement this pretty easily.

I will provide further documentation in the coming days (today is 3/20/2013...gotta keep myself honest ;) ).

=============

This commit also includes two additional classes:
  * Connector.php
      Connects to a database using a basic switch. Returns a MySQLi handle.
  * Logger.php
      Logs errors, responses, and additional lines. Pass the log filename on class instantiation.
