# Steps to Publish a VSCode Plugin

1. Install tools

```sh
brew install npm
npm install -g yo generator-code
npm install -g vsce
```

2. Get a token from AZure DevOps

3. Change to package root diectory and login

```sh
vsce login ShixiangWang
```

4. Publish

```sh
# AZURE TOKEN is a variable storing previous token
vsce publish -p $AZURE_TOKEN
```

A way to package

```sh
vsce package
```