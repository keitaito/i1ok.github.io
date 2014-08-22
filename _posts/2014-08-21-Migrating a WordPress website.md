---
layout: post
title: Migrating a WordPress website
---

I have moved my WordPress website from an old domain to a new one just now. I leave a note about what I did.

I wanted my new portfolio website at my main domain, keitaito.com without using WordPress. Because, I wanted to make my portfolio page be simple as much as I can. Also, I wanted to edit its layout with CSS and Bootstrap. To edit WordPress page, I am required to have PHP knowledge but I don't. That's one of the reasons I didn't want to use wp for my portfolio page.

First, I created a new sub domain, wp.keitaito.com, to move my WP website there. Since I'm using bluehost, it was easy to make a new subdomain from cPanel.

Second, I migrated my wp website from the main domain to the new subdomain. Check out this page, [How to migrate a WordPress site](https://my.bluehost.com/hosting/help/wordpress-migrate#setup). I installed WP at wp.keitaito.com to migrate my page. Then, I migrated my page with using ManageWP. Before migrating, I had already created a new subdomain and WP was already installed there, I didn't need to choose temporary URL. Checked out my new WP website, booom! It's working well!

Third, it's time to delete my old WP page. Before deleting, just in case, I backed it up with [Duplicator](https://wordpress.org/plugins/duplicator/). From cPanel file manager, I couldn't upload several files and folders, I used Filezilla. I got FTP configuration file from cPanel FTP Accounts. After making a backup archive file, I moved all files related to my old WP page to another directory. Then, I put my new portfolio page html file at keitaito.com (it means public_html.)

Now, [my new portfolio page](http://keitaito.com/) is working! This page and wp.keitaito.com page too! Success!!!
