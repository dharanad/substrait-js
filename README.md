
# susbtrait-js
JS support for Substrait.

## Development setup

Clone the github repository

```
git clone https://github.com/substrait-io/substrait-js.git
cd substrait-js/
git submodule update --init --recursive
```

Installation includes the following steps:
 1. Transpiling the `.ts` files
 2. Downloading the substrait specification
 3. Packaging the specifications to static `.js` module.

```
npm ci
npm run build
```
    
## License
[Apache-2.0 license](https://www.apache.org/licenses/LICENSE-2.0)
