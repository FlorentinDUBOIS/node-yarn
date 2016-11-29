# node-yarn
Node.js official docker with yarn built-in, and use yarn as package manager

## Build available
> This is a list of available docker by tag

* latest, onbuild
* 7, 7-onbuild
* 6, 6-onbuild
* 4, 4-onbuild
* boron, boron-onbuild
* argon, argon-onbuild

## Usage

### onbuild
> This tag is for encapsulate your application, you just have to create in your project a Dockerfile like this:

```Dockerfile
FROM florentindubois/node-yarn:onbuild
```

Do not forget to add the command EXPOSE if you use some ports

### node
> This part is for your test or your own implements yarn is a global command, so you can use it as you wish

example:

```Dockerfile
FROM florentindubois/node-yarn:latest

# Your stuff with yarn
```
