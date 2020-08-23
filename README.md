# electron-parcel-reloaded
Reload-enabled electron + parcel development environment

https://qiita.com/eihigh/items/0aaf064014c5b1e72282

## Usage
### Installation
```
npm install
```

### Start watching for renderer process
```
npm run watch
```
At this point, electron is not yet started.

### Start electron
```
npm run start
```
Automatic reloading is enabled, so if you change the source, the content will be reloaded.
