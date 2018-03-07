# difference between chai.should and should

## chai.should

```javascript
const { should } = require('chai')
should()

'abc'.should.be.a.string
should(undefined).equal(undefined)
```

## should

```javascript
require('should')

'abc'.should.be.a.string
should(undefined).be.undefined
```
