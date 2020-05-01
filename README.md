# ML-Model-CI

[![Build Status](https://travis-ci.com/cap-ntu/ML-Model-CI.svg?token=SvqJmaGbqAbwcc7DNkD2&branch=master)](https://travis-ci.com/cap-ntu/ML-Model-CI)

## Features

- Manager provides a refined management for model registration, deletion, update and selection.
- Converter is to convert models between frameworks.
- Diagnoser is to diagnose models and provides a detailed report about model performance in production environment.
- Deployer is to place models to devices and serve them automatically.

## Quick Start

### Installation

- [ ] step by step

<ol>
<li> Install MongoDB service </li>

```shell script
docker --rm -d -p 27017:27017 --name modelci-mongo mongo
```
And init database by:  
Go into the docker
```shell script
docker exec -ti modelci-mongo mongo
```
And create user:
```
> use modelci
switch to db modelci
> db.createUser({user: "modelci", pwd: "modelci@2020", roles: ["readWrite"]});
Successfully added user: { "user" : "modelci", "roles" : [ "readWrite" ] }
> exit
bye
```

</ol>

### Example

- [ ] a brief example (register, convert, dianose and deploy)

## Benchmark

- [ ] ModelZoo with model performance
