# bitnovex-pool-list

The goal of this repository is to have a central list of pools for BitNovex (https://www.bitnovex.com) mining. If you run a pool, please submit a Pull Request against *v2/bitnovex-pools.json* to get added.

This list can be consumed in your application so you'll always have an up-to-date list of pools. To consume the list, just use the following URL: https://raw.githubusercontent.com/BitNovex/bitnovex-pools-json/master/v2/bitnovex-pools.json

## Contributing

Please add your pool to the list in **alphabetical order**, named using CamelCase.domain style, and **include trailing slashes** for the `url` and `api` values.

**e.g.**
```
    {
        "name" : "MyPool.com",
        "url" : "https://btnx.mypool.com/",
        "api" : "https://btnx.mypool.com/api/",
        "type" : "forknote"
    },
```

### Possible values for 'type'
 - forknote
 - forknote-alt
 - node.js
 - other
