# Bake

### Install

```
brew tap markgarrigan/tools/bake
```

### Usage

The first thing you need to do is initialize the development environment.

```
bake dev

Options

-i | --image  The image for your development server. Default (node:12.16.2)
-n | --name  The name of your app. Default (appname)
-d | --dir  The working directory of your app. Default (/service/app)
-v | --volume  The name of the shared docker volume. Default (random string)
-c | --cmd  The command to run on start up. Default (npm start)
-t | --temp  The location of a temporary directory for template files. Default (./tmp)
-s | --ssl  Create local certs for https. Default (true)
```

Now you can initialize an npm package.

```
bake npm init
```

Then install some packages. First get to a bash prompt.

```
bake bash
```

Then install any npm package.

```
npm install express
```

When you're done npm installing.

```
exit
```

Run your development environment.

```
bake