# Federal Front Door Microsite

This repository contains the files and infrastructure to run the Federal Front
Door Microsite.

The microsite depends on the following projects:

- [Hugo](http://gohugo.io "Hugo Homepage"), a static-site generator written in Go.
- [Gulp](http://gulpjs.com "GulpJS Homepage"), an automation tool for asset-pipelines.

## Installing Hugo

In order to serve the microsite locally, you will need to install the `hugo`
command-line tool. This can be installed easily via [Homebrew][homebrew-install]
on Mac OS X with the following command in your Terminal.

[homebrew-install]: http://brew.sh "Homebrew Installation"

```shell
brew update && \
brew install hugo
```

You can also [download the latest release][hugo-release] and checkout the
[quick start guide][hugo-quick-guide] for further instructions.

[hugo-release]: https://github.com/spf13/hugo/releases "Download Latest Hugo Release"
[hugo-quick-guide]: http://gohugo.io/overview/quickstart/ "Hugo Quickstart Guide"

## Installing Gulp

In order to build the assets for the microsite, you will need to install the
`gulp` command-line tool. Because Gulp depends on `npm` and `node` during
runtime, please make sure you have them installed on your system. Instructions
for installing `node`, including `npm`, [can be found here] [node-install].

[node-install]: https://nodejs.org/en/download/ "NodeJS Downloads"

```sh
npm install --global gulp-cli
```

Once `gulp` is installed locally, navigate to this directory in your Terminal
and run `npm install` to bring in the asset-pipeline's dependencies. Once that
is complete, run `gulp` in your Terminal to get a list of available commands.
