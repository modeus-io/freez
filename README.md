<p align="center">
  <a href="https://github.com/modeus-io/glacial">
    <img width="200" src="assets/glacial-logo.png">
  </a>
</p>

<h1 align="center">Freez</h1>

<p align="center">Freez is a NodeJS library that reliably pipes a stream of bytes into an Amazon S3 Glacier vault</p>

**Installation**
---
```sh
yarn install -g freez
```

or  

```sh
npm install -g freez
```

**How to use it**
---

**Command Line:**

```sh
echo "Freeeeez" | freez
```

**NodeJS:**

```javascript
const Freez = require('freez');
const fz = Freez();

process.stdin.pipe(fz);
```


