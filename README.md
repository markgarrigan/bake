# Bake

### Install

```
brew tap markgarrigan/tools/bake
```

### Usage

The first thing you need to do is initialize Docker Compose.

```
bake dock
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

Run your development environment.

```
bake