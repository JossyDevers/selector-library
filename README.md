# selector-library
This is a example library used for the purpose of the developer blog https://gaute.app/dev-blog/npm-publish, demonstrating how to publish a NPM module and through a CDN.

Library to select elements the jQuery way, without needing to import all the jQuery stuff

## Installation
a) npm Module

`$ npm i npm i selector-library --save`

b) CDN

`<script src="https://unpkg.com/selector-library"></script>`

## Usage
a) npm Module
```
import {$, $$} from 'selector-library';

$('#id-name').classList.add('added-class');
$$('.class-name').forEach(el => el.style.backgroundColor = 'red');
```

b) CDN
```
$('#id-name').classList.add('added-class');
$$('.class-name').forEach(el => el.style.backgroundColor = 'red');
```
