# sparkjs
## Installation

```
npm install spark-api
```

## Getting Started

```js
import { Spark } from 'spark-api';

const { Spark } = require('spark-api');
```

## Spark.send(question)

```js
const spark = new Spark({
  secret: 'secret',
  key: 'key',
  appid: 'appid'
});

spark.send('你是谁').then(response => {
  console.log(response); // 您好，我是科大讯飞研发的认知智能大模型，我的名字叫讯飞星火认知大模型。我可以和人类进行自然交流，解答问题，高效完成各领域认知智能需求。
}).catch(error => {
  console.error(error);
});

```
## License

[MIT](https://github.com/VineWeb/sparkjs).
