---
author: sandeep
comments: true
date: 2013-01-23 10:35:40+00:00
layout: post
link: http://www.lambdacurry.com/2013/01/sending-email-using-amazon-ses-with-attachments-from-php/
slug: sending-email-using-amazon-ses-with-attachments-from-php
title: Sending email using Amazon SES with attachments from php
wordpress_id: 639
---

This script is crazy - there is no known sane example on how to do this, so I had spend an inordinate amount of time hacking together this script. Basically, you need to replay the SMTP email composition to Amazon SES.

This code snippet should help everyone who is trying to put together a way to send email with attachments using SES from PHP.

https://gist.github.com/4604187
