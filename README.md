## Portal demo using Nuxt.js + OAuth2

### Source code

- Clone source at:
`https://bitbucket.org/trunglecntt/portal-demo/src/master/`

### Dependencies

- Global package:
```
npm install -g nuxt
npm install -g grunt-cli
```
- Project dependencies
```
npm install
```
### Build & Deploy
- Run server: `grunt dev`
- Run parallel with API: `grunt mock`
- Build: `nuxt build && nuxt export`
- Deploy: Copy all items in `./dist` to server or S3 bucket
---
Happy coding :beer:
