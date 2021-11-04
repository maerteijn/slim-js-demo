# DonkeyJS
A plain simple javascript component framework.


Simple example:

```javascript
import Component from "donkeyjs/component"


class HelloWorld extends Component {
  template(state) {
    return `
      <h1>${state.title}</h1>
    `
  }
}

export default HelloWorld
```