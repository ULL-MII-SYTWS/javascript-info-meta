# Cloning this repo

Install [Git](https://git-scm.com/downloads) and [Node.js](https://nodejs.org). 

Please use Node.js 10+.



Install [meta](https://www.npmjs.com/package/meta) in your machine.
Install global Node modules:

```bash
npm install -g meta bunyan gulp@4
```

Run:

```
$ meta git clone git@github.com:ULL-MII-SYTWS/javascript-info-meta.git
...
```

Then `cd server` and issue `meta git update`

```
javascript-info-meta git:(master) cd server
server git:(master) meta git update
Clonando en 'modules/engine'...
remote: Enumerating objects: 136, done.
...
```

Install dependencies:

```
 server git:(master) npm i
```

Now run the server:

```
npm run server
```

You can see it running in `localhost:3000`

## See also

* [Tutorial to Install the Server](https://github.com/javascript-tutorial/server)
* [The Modern JavaScript Tutorial GitHub Organization](https://github.com/javascript-tutorial)
