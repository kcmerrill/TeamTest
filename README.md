TeamTest
========

Currently teamtest is a simple test runner. Configure a project with a basepath, TeamTest will poll/watch the directory and run any associated tests you've created.

A green tab means your test passed! An orange means it failed. Click on the test tabs to see the output of each test. 


![ScreenShot](https://raw.github.com/kcmerrill/TeamTest/master/www/images/tt/preview.png)

Version 2.0 will be a way to gameify testing, by allowing points based on various activities.   


Quick Start
===========

This project makes use of wikidiff2. To install this under Ubuntu do a:

    `sudo apt-get install php-wikidiff2`

Clone the repository with a:

    `git clone https://github.com/autowitch/TeamTest.git`
    
Now go into the new repository and set it set up:

    `cd TeamTest/`

    `php ./dev-install.php`
    `cd www/`

