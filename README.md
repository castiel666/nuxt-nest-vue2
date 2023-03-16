

## Getting started

### MySql

1. Create the `nest_cms_api` table;

2. Use MySql command or management software to import the `.sql` file in the `DB` directory.

### CMS API server

```bash
cd server

npm install

# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

- Serve: [http://localhost:3000/](http://localhost:3000/)
- API documentation: [http://localhost:3000/api/](http://localhost:3000/api/)
- Configuration: [config.default.ts](server/config/config.default.ts)

### CMS management

```bash
cd admin

npm install --legacy-peer-deps

# serve with hot reload at localhost:3002
npm run dev

# build for production and launch server

npm run build:stage

npm run build:prod
```

- Serve: [http://localhost:3002/](http://localhost:3002/)

### CMS web

```bash
cd web

npm install

# development
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

- Serve: [http://localhost:3001/](http://localhost:3001/)


