# Small Victories CLI

The Small Victories CLI is used to build Small Victories sites from the command line.

For more information about Small Victories see the [Small Victories Homepage](https://www.smallvictori.es).

For problems directly related to the CLI, [add an issue on GitHub](https://github.com/smallvictories/sv-cli/issues/new).

For questions or to get in touch, find us on [Twitter](https://twitter.com/smvico).

## Installation

### Homebrew (OS X)

Homebrew can be installed via [brew.sh](http://brew.sh)

```
$ brew install sv
```

### Zip Archives (OS X, Linux, Windows)

Bare zip archives per release version are available at https://github.com/smallvictories/sv-cli/releases/

## Verify

To verify you have successfully installed the Small Victories CLI, use the sv --version command:

```
$ sv --version
```

You should see a response of sv/x.y.z. If you don’t then the Small Victories CLI has not been installed correctly.

## Getting Started

First, you need to create a new folder for your site.

```
$ mkdir ~/site
```

Then you need to move into the site folder.

```
$ cd ~/site
```

Now you need to create an `_sv_settings.txt` file which has a `theme` attribute.

```
$ echo 'theme: blank' > _sv_settings.txt
```

The theme attribute tells the Small Victories CLI which type of Small Victories site to build. You can find more information on the different types of themes Small Victories supports below.

Finally you can run the Small Victories CLI to generate and server your site.

```
$ sv start
```

You now view your site at http://localhost:2015

SV will automatically watch for changes and rebuild your site as you add and update files in the site folder.
