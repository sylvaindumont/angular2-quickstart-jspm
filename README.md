#Angular2 Quickstart JSPM

An example for an Angular2 application with **typescript compilation inside browser** and dependencies management via jspm.

#### Requirements
node 5+

#### How to start
```
npm install
```

#### How to develop
import regular javascript dependencies (shims in our case)
```
import 'reflect-metadata';
```

import typescript elements
```
import {Component} from 'angular2/core';
```

#### Build for production
```
node_modules/.bin/jspm bundle dist/app
```
