---
title: "How does HTML5 file uploading work?"
date: "2023-02-16T15:21:54+05:30"
featured: true
featureImage: "blog/file-upload.jpg"
draft: false
weight: 3
---

#  How does file upload work?

File upload works in a rather simple way.

This thread illustrates it.

{{< rawhtml >}}
<blockquote class="twitter-tweet"><p lang="en" dir="ltr"><a href="https://t.co/iHek4CD4EG">https://t.co/iHek4CD4EG</a><br><br>How to create a file upload backend?<br><br>HTML5 file API based upload needs backend to go with frontend.<br><br>We discuss the backend in this thread.</p>&mdash; Girish Venkatachalam (@girish1729) <a href="https://twitter.com/girish1729/status/1625476765593526273?ref_src=twsrc%5Etfw">February 15, 2023</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
{{< /rawhtml >}}

Most uploads use HTTP `POST` or `PUT` method to accomplish file upload.

HTTP has a progress event to keep us displaying ETA, bytes uploaded
along with other data which we can use to show progress.

It is really useful to get this progress display right and engaging and
that is the primary purpose of this plugin.

All others are mere details.

## Backend

This article
[Which backend file uploader to
choose?](https://bytearcher.com/articles/formidable-vs-busboy-vs-multer-vs-multiparty/)
can teach you a lot about the communication between file upload frontend
and backend.

In this project [Express](https://expressjs.org) is used. We could use
anything that matches the files array name we give in the frontend.

The protocol to be used should be multipart-form-data and method should
be POST.

That is the reason there is a test upload feature in the tool.

## Frontend

The frontend is the one doing all the heavy-lifting.

That is the reason there is preview, upload progress display, statistics
reporting and other goodies.

However you may wish to do more or less.

Simply by plugging this into your applications you can solve a very
important problem in a cool way.

## Backend

The backend of file upload is described in this Twitter thread.

{{< rawhtml >}}
<blockquote class="twitter-tweet"><p lang="en" dir="ltr"><a href="https://t.co/iHek4CD4EG">https://t.co/iHek4CD4EG</a><br><br>How to create a file upload backend?<br><br>HTML5 file API based upload needs backend to go with frontend.<br><br>We discuss the backend in this thread.</p>&mdash; Girish Venkatachalam (@girish1729) <a href="https://twitter.com/girish1729/status/1625706890721382400?ref_src=twsrc%5Etfw">February 15, 2023</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
{{< /rawhtml >}}

A file upload process is communication between frontend and backend
using a agreed upon protocol.

This plugin focuses on the frontend but the backend must be setup
correctly to work properly.

And the frontend supports a test upload feature to test the basic
protocol with the backend.

Whenever you get stuck, it is best to check the test upload to see if
the backend is reachable and if things are setup correctly.

Also the frontend does not allow you to upload till some things are
configured and the values make sense.

[Back to blog](/blog)
