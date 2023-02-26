---
title: "Angular plugin"
date: "2023-02-16T15:21:54+05:30"
featureImage: "blog/angular.webp"
draft: false
---

# Angular plugin development

Angular is one of the most popular web development frameworks for single
page applications.

Angular has evolved over time with a focus on pure typescript code, CSS
for each template and a rich plugin ecosystem.

The build tools have also changed over time with a rather intensive
development process.

In this article we shall see how the Angular plugin was built for
progress-up.

## Plugin architecture

The plugin has only 3 files.

- progress-up.component.css
- progress-up.component.html
- progress-up.component.ts

And a progress-up.module.ts

The plugin has most of the functionality in the typescript file and the
HTML template.

## How it works?

Angular has a very sophisticated build system as well as a pure
typescript approach to development where javascript third party plugins
cannot be used.

But progress-up uses the progress loaders from
[loading.io](https://loading.io) which is written in javascript.


## How you can use the plugin?

{{<rawhtml>}}
<div class="flex justify-center">
<a href="https://angular-ivy-pu628h.stackblitz.io" class="bg-blue-200 rounded shadow-md text-black px-4 py-3 no-underline">Stackblitz </a>
</div>
{{</rawhtml>}}


The stackblitz link has the instructions and help needed.

In short, just installing using npm or yarn like this will get you
started.

```shell
	$ yarn install progress-up-angular
```

or

```shell
	$ npm install progress-up-angular
```

Then just put this inside the HTML source the tags needed and you are
done.

```html
	<progress-up></progress-up>
```

## Challenges

The plugin development had a lot of difficulties, but then the build
process and testing was very labor intensive since the linking involved
a lot of reinstalls.

Angular takes a really long time to build everytime.

And the caching is very annoying too. You need to delete the `.angular`
directory as well or you see the cached version.

[Back to blog](/blog)
