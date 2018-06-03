# Watcher

A hot reload watcher for laravel-swoole.

## Installation

* Copy `watcher.js` to your laravel project and add some dependencies to your `package.json`.

```json
"devDependencies": {
    "chokidar": "^2.0.3",
    "colors": "^1.2.5",
    "is-running": "^2.1.0"
}
```

* Install dependencies.

```
yarn install
```

* You're good to go.

```
node watcher.js
```
