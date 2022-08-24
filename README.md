# Getting Started with Reveal.js

Some reveal.js features, like external Markdown, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

## Download and Install

Make sure you have [Node.js](https://nodejs.org/) (10.0.0 or later) installed. Then, clone the reveal.js repository:

```shell
git clone https://github.com/hakimel/reveal.js.git
```

https://user-images.githubusercontent.com/20434532/186534494-464ed529-1a0a-4a1d-a5ed-4b1afdf649cb.mov

Next, move to the reveal.js folder and install dependencies:

```shell
cd reveal.js
npm install
```

https://user-images.githubusercontent.com/20434532/186534737-250675a6-bfd4-46d1-920b-c59350dcfeb7.mov

## Run the Demo

Serve the presentation and monitor source files for changes:

```shell
npm start
```

https://user-images.githubusercontent.com/20434532/186534880-5fe2d60b-756c-4d0d-97cc-3f94b5d62ba7.mov

Then, open http://localhost:8000 to view your presentation!

https://user-images.githubusercontent.com/20434532/186535100-205490a8-ba49-43b6-8df7-793f84aa6cba.mov

Any changes you make to the source files will be reflected in the presentation automatically.
