```js
var foo = 10;

(function() {
  this.foo; //: number
})();
```
```json
[
  {
    "name": "foo",
    "addr": "/foo/",
    "kind": "v",
    "type": "number",
    "lineno": 1,
    "tagfile": "/usr/local/lib/node_modules/jsctags/test/cases/global_this.js"
  }
]
```
```ctags
foo	/usr/local/lib/node_modules/jsctags/test/cases/global_this.js	/foo/;"	v	lineno:1	type:number
```
