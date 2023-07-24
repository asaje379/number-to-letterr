# number-to-letter

> yagoubigithub/convertir-nombre-chiffre typescript version for number to letter conversion in french

## Install

### npm

```bash
npm i number-to-letter-ts
```

### yarn

```bash
yarn add number-to-letter-ts
```

## Usage

```ts
import { NumberToLetter, FloatToLetter } from 'number-to-letter-ts';
console.log(NumberToLetter(12)); // print 'douze'
console.log(FloatToLetter(12)); // print 'douze'
console.log(FloatToLetter(12.1234)); // print 'douze virgule douze' : precision of 2 by default
console.log(FloatToLetter(12.125, 3)); // print 'douze virgule cent vingt-cinq'
```
