# Kendo UI Professional jQuery Angular 1 Boilerplate

A Kendo UI Professional jQuery Angular 1 boilerplate to get you started.

### Prerequisites

First, install or update [Node.js & npm](https://nodejs.org/).

Once you have Node.js/npm working open a terminal and install [ower](http://bower.io/) and [browsersync](https://www.browsersync.io/) globally by running (might have to [sudo](https://support.apple.com/en-us/HT202035)):

```
$ npm install bower browser-sync -g
```

### Installing

Download a [ZIP](https://github.com/kendo-labs/kendo-ui-boilerplates/archive/master.zip) of this [repository](https://github.com/kendo-labs/kendo-ui-boilerplates) (i.e. kendo-ui-boilerplates).

Or, if you have GIT installed you can Git clone this [repository](https://github.com/kendo-labs/kendo-ui-boilerplates).

SSH:

```
$ git clone git@github.com:kendo-labs/kendo-ui-boilerplates.git
```

https:

```
$ git clone https://github.com/kendo-labs/kendo-ui-boilerplates.git
```

Select the boilerplate you'd like to use from the directory you just downloaded/cloned and `cd` into that directory from a terminal.

Then run the following commands from the directory of the boilerplate you selected:

```
$ npm install
```

and (You'll be asked for your Telerik username and password credentials):

```
$ bower install
```

Note: In order to avoid retyping your credentials, you may cache them. The easiest way to do that is to store them as plain text in a [.netrc file](http://www.mavetju.org/unix/netrc.php). See the [documentation for more details](http://docs.telerik.com/kendo-ui/intro/installation/bower-install#kendo-ui-professional).

This will install the required [npm](https://www.npmjs.com/) and [Bower](http://bower.io/) packages.

### Running

Open a terminal from the boilerplate directory. You should have one open at this point.

Run the following [npm scripts](https://docs.npmjs.com/misc/scripts) commands:

```
$ npm run dev-server
```

This will open the `index.html` page at localhost:4000 in your default browser using [browsersync](https://www.browsersync.io/). Browsersync has been setup to reload after any changes to any `.html`, `.css`, or `.js `files in the `dev-server` directory.

## License

This project has been released under the [Apache License, version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)
