# selector-library
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
