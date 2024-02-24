```js

const { bing } = require("nayan-bing-api");
const request = require('request')

const key = "Nayan" //dont change key

const cookie = "cooki" //past your bing cookie here

const prompt = "cat" // write a promt

bing(prompt, cookie, key).then(data => {
  console.log(data)
});
```
