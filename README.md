# prettier-config
Shared prettier config for all typescript projects

Example How to add it your repository (package.json):
```
{
  "dependencies": {
    "@doo/prettier-config": "https://github.com/doo/prettier-config.git"
  }
}
```


Example how to use this package in your typescript project (.prettierrc.js):
```
module.exports = {
  ...require("@doo/prettier-config"),
};
```
