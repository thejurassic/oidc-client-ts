![Pipeline](https://github.com/pamapa/oidc-client-ts/workflows/Release/badge.svg)

# oidc-client-ts
Library to provide OpenID Connect (OIDC) and OAuth2 protocol support for client-side, browser-based JavaScript client applications. Also included is support for user session and access token management.

This is a forked version of the [oidc-client-js](https://github.com/IdentityModel/oidc-client-js) library, which has been archived and is no longer maintained. This version has been refactored from JavaScript to TypeScript. Trying to keep the API, as compatible as possible.

However we are aiming to modernize and simplify some internal parts, which will have an effect on the API. See the [milestone](https://github.com/pamapa/oidc-client-ts/milestone/1) for more info. IE11 will no longer be supported.

**Contributions and help is much appreciated!**

## Table of Contents
- [Documentation](#documentation)
- [Installation](#installation)
- [Building the Source](#building-the-source)
- [Contributing](#contributing)
- [License](#license)

## Documentation

Some initial docs are [here](https://github.com/IdentityModel/oidc-client-js/wiki).


## Installation

Using [npm](https://npmjs.org/)

```bash
npm install react-oidc-context
```

## Building the Source

```bash
git clone https://github.com/pamapa/oidc-client-ts.git
cd oidc-client-ts
npm install
npm run build
```

### Running the Sample

```bash
npm start
```

and then browse to [http://localhost:15000](http://localhost:15000).

### Running the Tests

```bash
npm test
```

## Contributing

All are welcome on the [issue tracker](https://github.com/pamapa/oidc-client-ts/issues).

## License
This project is licensed under the Apache-2.0 license. See the [LICENSE](https://github.com/pamapa/oidc-client-ts/blob/main/LICENSE) file for more info.
