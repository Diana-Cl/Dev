# Kickass markdown
A collection of Github markdown tricks for writing kickass READMEs, Pull Requests & Comments.  
Markdown is Github's version of dress code - Make your first impression count.

<br>

## More 

> [Getting started writing on GitHub](https://docs.github.com/en/get-started/writing-on-github/)  
> [markdown hacks](https://www.markdownguide.org/hacks/)  
> [markdown basic-syntax](https://www.markdownguide.org/basic-syntax/)  
> [flavoured markdown](https://docs.github.com/en/get-started/writing-on-github/)  
> [markup engine](https://github.com/github/markup/)   
> [LaTeX Mathematics](https://en.wikibooks.org/wiki/LaTeX/Mathematics/)
> [By John Gruber](http://daringfireball.net/projects/markdown/)  
> 

<br>

### Writing on GitHub
> [You can structure the information shared on GitHub with various formatting options](https://docs.github.com/en/get-started/writing-on-github).
>
> At the end Make sure to checkout [README-Full.md](README-Full.md) for all common page elements.

<br>

### What tricks can I use?
READMEs offer support for:  

👉 [Emoji cheat sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)  
👉 [Markdown](#markdown-tricks)  
👉 [HTML](#html-tricks)

<br>

## Markdown tricks

```diff
+ this text is highlighted in green
- this text is highlighted in red
```

<pre>
```diff
+ this text is highlighted in green
- this text is highlighted in red
```
</pre>

---

```CSS
Some text in green! 123
```

<pre>
```CSS
Some text in green! 123
```
</pre>

---

```P4
Some text in blue! 123
```

```Mint
Some text in blue with additional keyword highlighting! 123
```

<pre>
```P4
Some text in blue! 123
```

```Mint
Some text in blue with additional keyword highlighting! 123
```
</pre>

---

```robots.txt
some text in light blue! 123
```

<pre>
```robots.txt
some text in light blue! 123
```
</pre>

---

```EBNF
Some text in purple! 123
```

```mupad
Some text in purple with additional keyword highlighting! 123
```

<pre>
```EBNF
Some text in purple! 123
```

```mupad
Some text in purple with additional keyword highlighting! 123
```
</pre>

---

```Mathematica
Some text in orange! 123
```

```REXX
Some text in orange with additional keyword highlighting! 123
```

```Nix
Some text in orange with additional keyword highlighting! 123
```

<pre>
```Mathematica
Some text in orange! 123
```

```REXX
Some text in orange with additional keyword highlighting! 123
```

```Nix
Some text in orange with additional keyword highlighting! 123
```
</pre>

---

```POV-Ray SDL
some text in red!
```

<pre>
```POV-Ray SDL
some text in red!
```
</pre>

---

```RobotFramework
Some text in light red! 123
```

<pre>
```RobotFramework
Some text in light red! 123
```
</pre>

---

```JSON
Some text highlighted in red! 123
```

<pre>
```JSON
Some text highlighted in red! 123
```
</pre>

## HTML tricks

<samp>Monospaced text</samp>

```
<samp>Monospaced text</samp>
```

---

<ins>Underlined text</ins>

```
<ins>Underlined text</ins>
```

---

<table><tr><td>Boxed text</td></tr></table>

```
<table><tr><td>Boxed text</td></tr></table>
```

---

<details>
<summary>Item summary with dropdown</summary>

Dropdown content (supports **markdown** ~~yay!~~)

```json
{
  awesome: "true"
}
```
</details>

<pre>
&lt;details>
&lt;summary>Item summary with dropdown&lt;/summary>

Dropdown content (supports **markdown** ~~yay!~~)

```json
{
  awesome: "true"
}
```
&lt;/details>
</pre>

---

__*Italic-bold*__

```
__*Italic-bold*__
```

---

Superscript<sup>TM</sup>

```
Superscript<sup>TM</sup>
```

---

Superscript-italic<sup>*tm*</sup>

```
Superscript-italic<sup>*tm*</sup>
```

---

Subscript<sub>x</sub>

```
Subscript<sub>x</sub>
```

---

Subscript-bold<sub>**min**</sub>

```
Subscript-bold<sub>**min**</sub>
```

---

~~__*Italic-bold-strikethrough*__~~

```
~~__*Italic-bold-strikethrough*__~~
```



# Dillinger
## _The Last Markdown Editor, Ever_

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Dillinger is a cloud-enabled, mobile-ready, offline-storage compatible,
AngularJS-powered HTML5 Markdown editor.

- Type some Markdown on the left
- See HTML in the right
- ✨Magic ✨

## Features

- Import a HTML file and watch it magically convert to Markdown
- Drag and drop images (requires your Dropbox account be linked)
- Import and save files from GitHub, Dropbox, Google Drive and One Drive
- Drag and drop markdown and HTML files into Dillinger
- Export documents as Markdown, HTML and PDF

Markdown is a lightweight markup language based on the formatting conventions
that people naturally use in email.
As [John Gruber] writes on the [Markdown site][df1]

> The overriding design goal for Markdown's
> formatting syntax is to make it as readable
> as possible. The idea is that a
> Markdown-formatted document should be
> publishable as-is, as plain text, without
> looking like it's been marked up with tags
> or formatting instructions.

This text you see here is *actually- written in Markdown! To get a feel
for Markdown's syntax, type some text into the left window and
watch the results in the right.

## Tech

Dillinger uses a number of open source projects to work properly:

- [AngularJS] - HTML enhanced for web apps!
- [Ace Editor] - awesome web-based text editor
- [markdown-it] - Markdown parser done right. Fast and easy to extend.
- [Twitter Bootstrap] - great UI boilerplate for modern web apps
- [node.js] - evented I/O for the backend
- [Express] - fast node.js network app framework [@tjholowaychuk]
- [Gulp] - the streaming build system
- [Breakdance](https://breakdance.github.io/breakdance/) - HTML
to Markdown converter
- [jQuery] - duh

And of course Dillinger itself is open source with a [public repository][dill]
 on GitHub.

## Installation

Dillinger requires [Node.js](https://nodejs.org/) v10+ to run.

Install the dependencies and devDependencies and start the server.

```sh
cd dillinger
npm i
node app
```

For production environments...

```sh
npm install --production
NODE_ENV=production node app
```

## Plugins

Dillinger is currently extended with the following plugins.
Instructions on how to use them in your own application are linked below.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantaneously see your updates!

Open your favorite Terminal and run these commands.

First Tab:

```sh
node app
```

Second Tab:

```sh
gulp watch
```

(optional) Third:

```sh
karma test
```

#### Building for source

For production release:

```sh
gulp build --prod
```

Generating pre-built zip archives for distribution:

```sh
gulp build dist --prod
```

## Docker

Dillinger is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 8080, so change this within the
Dockerfile if necessary. When ready, simply use the Dockerfile to
build the image.

```sh
cd dillinger
docker build -t <youruser>/dillinger:${package.json.version} .
```

This will create the dillinger image and pull in the necessary dependencies.
Be sure to swap out `${package.json.version}` with the actual
version of Dillinger.

Once done, run the Docker image and map the port to whatever you wish on
your host. In this example, we simply map port 8000 of the host to
port 8080 of the Docker (or whatever port was exposed in the Dockerfile):

```sh
docker run -d -p 8000:8080 --restart=always --cap-add=SYS_ADMIN --name=dillinger <youruser>/dillinger:${package.json.version}
```

> Note: `--capt-add=SYS-ADMIN` is required for PDF rendering.

Verify the deployment by navigating to your server address in
your preferred browser.

```sh
127.0.0.1:8000
```

## License

MIT

**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
