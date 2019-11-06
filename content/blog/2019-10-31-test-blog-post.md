---
layout: blog
title: Test Blog Post
description: This is the first test blog post
date: 2019-10-31T06:41:02.739Z
thumbnail: /img/presto-pay-eligibility.png
rating: 4
---
## Enable Identity and Git Gateway

Netlify's Identity and Git Gateway services allow you to manage CMS admin users for your site without requiring them to have an account with your Git host or commit access on your repo. From your site dashboard on Netlify:



Go to **Settings > Identity**, and select Enable Identity service.

Under **Registration preferences**, select **Open** or **Invite only**. In most cases, you want only invited users to access your CMS, but if you're just experimenting, you can leave it open for convenience.

If you'd like to allow one-click login with services like Google and GitHub, check the boxes next to the services you'd like to use, under **External providers**.

Scroll down to **Services > Git Gateway**, and click **Enable Git Gateway**. This authenticates with your Git host and generates an API access token. In this case, we're leaving the **Roles** field blank, which means any logged in user may access the CMS. For information on changing this, check the **Netlify Identity documentation**.
