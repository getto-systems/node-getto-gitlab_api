# node-getto-gitlab_api

gitlab_api : getto-psycher vendor plugin

status: production ready

```javascript
const gitlab_api = require("getto-gitlab_api").init();

gitlab_api.trigger({
  project_id: "PROJECT-ID",
  token: "TOKEN",
  ref: "master",
  variables: {
    KEY: "VALUE",
  },
});
```


###### Table of Contents

- [Requirements](#Requirements)
- [Usage](#Usage)
- [License](#License)

## Requirements

- Node.js: 10.16.0


## Usage

```javascript
const gitlab_api = require("getto-gitlab_api").init();

gitlab_api.trigger({
  project_id: "PROJECT-ID",
  token: "TOKEN",
  ref: "master",
  variables: {
    KEY: "VALUE",
  },
});
```

### Install

```bash
npm install --save getto-gitlab_api
```


## License

node-getto-gitlab_api is licensed under the [MIT](LICENSE) license.

Copyright &copy; since 2019 shun@getto.systems

