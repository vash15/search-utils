# search-utils
Utils for search into string


```javascript
var str = 'bar Ristorante Da Pino';
console.log(search.splitWords(str));
console.log('cerca %s', 'bar', search.words('bar', str));
console.log('cerca %s', 'Foo', search.words('Foo', str));
console.log('cerca %s', 'rist', search.words('rist', str));
console.log('cerca %s', 'pino', search.words('pino', str));
console.log('cerca %s', 'Da pino', search.words('Da pino', str));
console.log('cerca %s', 'Ristorante da pino', search.words('Ristorante da pino', str));
console.log('cerca %s', 'bar da pino', search.words('bar da pino', str));
console.log('cerca %s', 'bar pino', search.words('bar pino', str));
console.log('cerca %s', 'foo pino', search.words('foo pino', str));
```
