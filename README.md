# difference between chai.should and should

## Try them

```shell
$ git clone https://github.com/kamataryo/chai.should_vs_should.git
$ cd chai.should_vs_should
$ npm i
$ node chai.js
$ node should.js
```

## abstract

### chai.should

```javascript
const { should } = require('chai')
should()

'abc'.should.be.a.string
should(undefined).equal(undefined)
```

### should

```javascript
require('should')

'abc'.should.be.a.string
should(undefined).be.undefined
```
