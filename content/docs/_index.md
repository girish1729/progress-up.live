---
title: "Progress-up documentation"
---

# Getting Started with progress-up

Progress-up is a simple file uploader easy to setup. It fetches files from local disk, and uploads them to the final destination. 

It’s fast simple to integrate and lets you think about more important
problems than building a file uploader. :smile:

Progress-up has various plugins for web development frameworks for easy
integration and quick setup.

It can also be used standalone. Check the demos below.

Here’s the simplest example html page with Progress-up (it uses a CDN bundle, while we recommend to use a bundler, see Installation):

{{<rawhtml>}}
<div class="flex justify-center">
<a target="_blank" href="https://stackblitz.com/edit/express-simple-wur94p"
class="bg-blue-600 rounded shadow-md text-black px-4 py-3
no-underline">HTML5 on Stackblitz </a>
</div>
{{</rawhtml>}}

[Running natively](/progress-up-html5) 



Drag and drop, preview for most file types, simple filters based on size
and MIME type are all available.

## Installation

Progress-up can be setup by including it in a script tag with some CSS
and HTML templating.

### Angular 

```shell
	$ npm install progress-up-angular
# or 
	$ yarn add progress-up-angular
```
### Vue 3

```shell
	$ npm install progress-up-vue
# or 
	$ yarn add progress-up-vue
```
### React.js

```shell
	$ npm install progress-up-react
# or 
	$ yarn add progress-up-react
```
### Svelte

```shell
	$ npm install progress-up-svelte
# or 
	$ yarn add progress-up-svelte
```



## Documentation

- Progress-up — full list of options, methods and events.

- Plugins — list of Uppy plugins and their options.

- Server — setting up and running a Companion instance, which adds support for Instagram, Dropbox, Google Drive, direct links, and other remote sources.

- React — components to integrate Uppy UI plugins with React apps.

- Writing Plugins — how to write a plugin for Uppy (documentation in progress).

- [Angular](/docs/angular-docs)
- [Vue.js](/docs/vue-docs)
- [React](/docs/react-docs)
- [Svelte](/docs/svelte-docs)

## Browser Support

We aim to support recent versions of Chrome, Firefox, Safari and Edge.
