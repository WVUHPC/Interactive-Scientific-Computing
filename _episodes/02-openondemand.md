---
title: "Open On Demand: Easy web access to HPC resources"
teaching: 30
exercises: 30
questions:
- "What is Open On Demand?"
- "Creating the first interactive session"
objectives:
- "First learning objective. (FIXME)"
keypoints:
- "First key point. Brief Answer to questions. (FIXME)"
---

Open OnDemand is an open-source HPC portal. Open OnDemand provides an easy way of getting web access to HPC resources, in particular we will demonstrate the use of Open OnDemand to create a session using Jupyter or RStudio, two popular web applications for scientific computing.

Open OnDemand has been configure at WVU to access computational resources on Thorny Flat, the biggest cluster at WVU.

In order to access Open OnDemand you should be in-campus network.
Try to access it on you browser:

<span style="font-size:larger;">
<a href="https://ondemand-tf.hpc.wvu.edu">
https://ondemand-tf.hpc.wvu.edu
</a></span>

You should get a page asking for authentication, like below.

<a href="{{ page.root }}/fig/OOD-CAS.png">
  <img src="{{ page.root }}/fig/OOD-CAS.png"
  alt="Central Authentication Service" height="400" />
</a>

If you are getting an error like:

<a href="{{ page.root }}/fig/OOD-OutCampus.png">
  <img src="{{ page.root }}/fig/OOD-OutCampus.png"
  alt="Out of Campus Error" height="200" />
</a>

You are out of campus network. You need a VPN to get access to resources available in-campus. Instructions to request access to WVU's VPN can be found here:

<https://wvu.teamdynamix.com/TDClient/1976/Portal/KB/ArticleDet?ID=100867>

Once you can establish secure connexion to in-campus resources access the Open OnDemand portal again. You will be greet with the authentication page.
Enter your username and password. After that you are directed to the DUO Two-Factor Authentication, where you have to either sent a Duo push to your mobile device or enter the passcode

<a href="{{ page.root }}/fig/OOD-Duo-Auth.png">
  <img src="{{ page.root }}/fig/OOD-Duo-Auth.png"
  alt="Duo Two-Factor Authentication" height="400" />
</a>

Once you have pass the Authentication step, you will be greet by the Open OnDemand Welcome Page.

<a href="{{ page.root }}/fig/OOD-Welcome.png">
  <img style="border:1px solid black;"
  src="{{ page.root }}/fig/OOD-Welcome.png"
  alt="Open OnDemand Welcome Page" height="400" />
</a>


{% include links.md %}
