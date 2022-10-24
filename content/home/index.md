# Progress.up HTML5 File Upload Progress indicator

![Progess.up](https://raw.githubusercontent.com/girish1729/progress.up/main/html5-upload/images/Progress.Up.png)

## What is this?

This is a HTML5 multiple files Upload plugin with progress bar
indicator.

This uses the HTTP File API protocol to show continuous progress.


>This is the very first attempt to create a clean no frills upload plugin
>in 100% Javascript. Now available for Angular, Vue and React.

[Canonical home page](https://progress-up.live)

Demos will be added soon to the above page :point_up: .

## Instructions

### Plain js

```shell
	$ npm add progress-up
```

### Angular 13+

```shell
	$ npm add progress-up/angular
```
### Vue 3

```shell
	$ npm add progress-up/vue
```
### React.js

```shell
	$ npm add progress-up/react
```

## Detailed instructions

- [Developer docs](https://progress-up.live/docs)
- [Live demo](https://progress-up.live/demo)
- [Vue.js](https://progress-up.live/vue)
- [Angular](https://progress-up.live/angular)
- [React](https://progress-up.live/react)
 

## Some me the code

{{<rawhtml>}}
<script src="https://emgithub.com/embed-v2.js?target=https%3A%2F%2Fgithub.com%2Fgirish1729%2Fprogress-up%2Fblob%2Fefd9731e390c8d355c3e048245c60a0de6c3a2df%2Fhtml5-upload%2Fjs%2FuploadProgress.js&style=default&type=code&showBorder=on&showLineNumbers=on&showFileMeta=on&showFullPath=on&showCopy=on"></script>
{{</rawhtml>}}

## Screenshots gallery

![Progess.up
screenshot](https://raw.githubusercontent.com/girish1729/progress.up/main/html5-upload/images/progress-up-html5-upload-capture.png)

## Why should you care?

If you allow multiple large files upload then a progress indicator is a
cool way to give user feedback.

Nowadays HTML5 File API based progress is the best way to achieve your
goal.

This project was written ground up with latest technology as of Oct 22,
2022.

However the status of project is `Beta`.

Most testing is needed. If you volunteer please [get in
touch](https://twitter.com/girish1729).

## How to build and run as plain js

**Instructions or frameworks coming soon**

```
$ git clone https://github.com/girish1729/progress.up
$ cd progress.up/html5-upload
$ yarn install

# or

$ npm install

$ mkdir uploads

$ npm start
```

Go to [http://localhost:2324](http://localhost:2324)

 and try uploading files.

You may use manual upload.

 Drag and drop into the shaded area is not implemented yet.

The uploaded files are present in `html5-upload/uploads` folder.

## Backend

This backend is [Node.js HTTP server express.js](https://expressjs.com) with [multer middleware](http://expressjs.com/en/resources/middleware/multer.html)

> This ensures that this code is platform agnostic.
> Most issues with file upload plugins extant today hover around
> not specifying backend correctly. Not making it easy to use.
> Not explaining what should be the input file name attribute etc.
> 

We require a backend that accepts `multipart/form-data` as upload
protocol.

Also the name of the `<input type='file` attribute should `myFiles`.

## Frontend - the plugin itself

It is using the HTML5 File API.

This is a clean way to get progress indicator for file uploads.

## Screencast of upload

![Progess.up screencast](https://raw.githubusercontent.com/girish1729/progress.up/main/html5-upload/images/progress-up-html5-upload-capture.gif)

## Next steps

Plugins for 

- [Vue.js](https://www.vuejs.org) 
- [Angular 12](https://angular.io) 
- [React JS](https://reactjs.org) 

are on the way.

- Adding drag and drop and image preview.

- Options for the plugin (theming, backend endpoint)

If you wish to collaborate or send pull requests 
please get in touch using my Github profile.

If you cannot write code, then buying me a coffee can work as well.
