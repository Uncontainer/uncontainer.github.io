+++
date = "2015-07-18T14:08:29+02:00"
draft = false
title = "Why Containers"
img = "docker-boat.jpg"
weight = 1
+++

We at Uncontainer, allow you to cleanly separate what has traditionally has been dumped on a single big server (which you can still use). 
Everything is concise, easy-to-understand, and easily replace-able components. 
For example, with Docker, it’s easy to swap out your Apache container for your nginx container in a way that doesn’t affect your application because it can run fine with any of your web server containers.

We built a platform for an innovative lending platform based on Docker which abstracted out redis, elasticsearch, postgresql, ruby on rails and celery. 
This platform was migrated from Rackspace -> AWS within a few hours as a consequence of containerization.
