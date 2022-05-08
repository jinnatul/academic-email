<div align='center'>

![npm](https://badgen.net/npm/v/academic-email)
![install size](https://badgen.net/packagephobia/install/academic-email)
![stars](https://badgen.net/github/stars/jinnatul/academic-email)
![npm](https://img.shields.io/npm/dw/academic-email)
![total downloads](https://badgen.net/npm/dt/academic-email)

</div>

## Academic Email Verifier
Identifies email addresses or domains names that belong to colleges or universities. Retrieves institution name or institution country.

```js
$ npm i academic-email
```

### Usage
```js
// es5
const academicEmail = require('academic-email');

// es6
import { isAcademic, getInstitutionName, getInstitutionCountry } from 'academic-email';

isAcademic('zinnatul35-1957@diu.edu.bd');
// => true

isAcademic('morol@diu.edu');
// => false

getInstitutionName('zinnatul35-1957@diu.edu.bd');
// => 'Daffodil International University'

getInstitutionName('morol@diu.edu');
// => 'Invalid email!'

getInstitutionCountry('zinnatul35-1957@diu.edu.bd');
// => 'Bangladesh'

getInstitutionCountry('morol@diu.edu');
// => 'Invalid email!'

```
