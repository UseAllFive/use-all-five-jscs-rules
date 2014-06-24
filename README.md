# use-all-five-jscs-rules

Custom UA5 JavaScript Code Sniffer rules.

### disallowVarHoisting

Disable variable hoisting. Variables must be declared at top of functional scope.

Type: `Boolean`
Values: `true`

#### Example

```js
"disallowVariableHosting": true
```

##### Valid

```js
var x;
var y;
x = 1;
```

##### Invalid

```js
var x;
x = 1;
var y;
```
