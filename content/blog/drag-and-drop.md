---
title: "Drag and drop files for upload"
date: "2023-02-16T15:21:54+05:30"
featureImage: "blog/drag-drop.webp"
draft: false
weight: 3
---

# Drag and drop 

File upload is best done using drag and drop without having to use a
file chooser.

The way I did the HTML5 drag and drop is quite simple.

All you had to do is plug into the events and you are done.

However I added the nice feature of background change on dragging over.

I find this will really help the usability.

The HTML5 spec is clear on drag and drop and this is well supported
across all browsers. Coding is simple too.

## Challenges

As such, drag and drop could easily be implemented across all platforms.

I did not face any major hassles or troubles.

The logic flow after dropping files is same as file upload from mouse
click.

The drop area being large, there should not be any trouble with the drag
and drop usability.

But at one time you must use either all files in drag and drop or file
select.

Right now, there is no mixed operation.

At one time you must select all files scheduled for uploading.

## How drag and drop helps

It is not just a convenience feature.

In each plugin drag and drop works a little differently as it is coded
differently.

But the functionality must be same.

The way the drag and drop function works in

- svelte
- angular
- vue
- react

is by tapping into `dragenter`, `dragleave` and `drop` events.

The way this works is similar to other javascript browser events.

Once the drop is complete drag and drop completes.

## How to use it in the plugin

It works by default.

When the files are dragged over the droppable region the background
color changes to blue.

This gives visual feedback to ease the upload process.

Every-time a new set of files are chosen for upload the old ones are
deleted from the upload queue.


[Back to blog](/blog)
