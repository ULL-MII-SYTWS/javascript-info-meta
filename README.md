# Cloming this repo

Install [meta](https://www.npmjs.com/package/meta) in your machine.

Run:

```
$ meta git clone git@github.com:ULL-MII-SYTWS/javascript-info-meta.git
...
```
Then `cd server` and issue `meta git update`

```
 javascript-info-meta git:(master) cd server
 server git:(master) meta git update
*** the following repositories have been added to .meta but are not currently cloned locally:
*** { 'modules/engine': 'https://github.com/javascript-tutorial/engine' }
*** type 'meta git update' to correct.

/Users/casianorodriguezleon/books/js/javascript-info-meta/server/modules/engine:
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
