# api documentation for  [cssnano (v3.10.0)](https://github.com/ben-eb/cssnano)  [![npm package](https://img.shields.io/npm/v/npmdoc-cssnano.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-cssnano) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-cssnano.svg)](https://travis-ci.org/npmdoc/node-npmdoc-cssnano)
#### A modular minifier, built on top of the PostCSS ecosystem.

[![NPM](https://nodei.co/npm/cssnano.png?downloads=true)](https://www.npmjs.com/package/cssnano)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cssnano/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-cssnano_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cssnano/build..beta..travis-ci.org/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-cssnano/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-cssnano/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ben Briggs",
        "email": "beneb.info@gmail.com",
        "url": "http://beneb.info"
    },
    "ava": {
        "require": "babel-core/register"
    },
    "bugs": {
        "url": "https://github.com/ben-eb/cssnano/issues"
    },
    "dependencies": {
        "autoprefixer": "^6.3.1",
        "decamelize": "^1.1.2",
        "defined": "^1.0.0",
        "has": "^1.0.1",
        "object-assign": "^4.0.1",
        "postcss": "^5.0.14",
        "postcss-calc": "^5.2.0",
        "postcss-colormin": "^2.1.8",
        "postcss-convert-values": "^2.3.4",
        "postcss-discard-comments": "^2.0.4",
        "postcss-discard-duplicates": "^2.0.1",
        "postcss-discard-empty": "^2.0.1",
        "postcss-discard-overridden": "^0.1.1",
        "postcss-discard-unused": "^2.2.1",
        "postcss-filter-plugins": "^2.0.0",
        "postcss-merge-idents": "^2.1.5",
        "postcss-merge-longhand": "^2.0.1",
        "postcss-merge-rules": "^2.0.3",
        "postcss-minify-font-values": "^1.0.2",
        "postcss-minify-gradients": "^1.0.1",
        "postcss-minify-params": "^1.0.4",
        "postcss-minify-selectors": "^2.0.4",
        "postcss-normalize-charset": "^1.1.0",
        "postcss-normalize-url": "^3.0.7",
        "postcss-ordered-values": "^2.1.0",
        "postcss-reduce-idents": "^2.2.2",
        "postcss-reduce-initial": "^1.0.0",
        "postcss-reduce-transforms": "^1.0.3",
        "postcss-svgo": "^2.1.1",
        "postcss-unique-selectors": "^2.0.2",
        "postcss-value-parser": "^3.2.3",
        "postcss-zindex": "^2.0.1"
    },
    "description": "A modular minifier, built on top of the PostCSS ecosystem.",
    "devDependencies": {
        "array-to-sentence": "^1.1.0",
        "ava": "^0.17.0",
        "babel-cli": "^6.5.1",
        "babel-core": "^6.5.1",
        "babel-loader": "^6.2.4",
        "babel-plugin-add-module-exports": "^0.2.0",
        "babel-plugin-precompile-charcodes": "^1.0.0",
        "babel-preset-es2015-loose": "^7.0.0",
        "babel-preset-stage-0": "^6.5.0",
        "coveralls": "^2.11.6",
        "cross-env": "^2.0.0",
        "css-frameworks": "git+https://git@github.com/ben-eb/css-frameworks.git",
        "css-minifier-tests": "git+https://git@github.com/ben-eb/css-minifier-tests.git",
        "del-cli": "^0.2.0",
        "eslint": "^3.0.0",
        "eslint-config-cssnano": "^3.0.0",
        "eslint-plugin-babel": "^3.3.0",
        "eslint-plugin-import": "^2.0.1",
        "gh-pages": "^0.11.0",
        "json-loader": "^0.5.4",
        "ncp": "^2.0.0",
        "nyc": "^10.0.0",
        "postcss-font-magician": "^1.5.0",
        "webpack": "^1.12.13",
        "webpack-bundle-size-analyzer": "^2.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "4f38f6cea2b9b17fa01490f23f1dc68ea65c1c38",
        "tarball": "https://registry.npmjs.org/cssnano/-/cssnano-3.10.0.tgz"
    },
    "eslintConfig": {
        "extends": "cssnano"
    },
    "files": [
        "dist",
        "LICENSE-MIT",
        "quickstart.js"
    ],
    "gitHead": "355c6ec30fe77a505f4b3c8d4c37db421e5109c8",
    "homepage": "https://github.com/ben-eb/cssnano",
    "keywords": [
        "css",
        "compress",
        "minify",
        "optimise",
        "optimisation",
        "postcss",
        "postcss-plugin"
    ],
    "license": "MIT",
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "beneb",
            "email": "beneb.info@gmail.com"
        },
        {
            "name": "trysound",
            "email": "trysound@yandex.ru"
        }
    ],
    "name": "cssnano",
    "nyc": {
        "exclude": [
            "node_modules",
            "**/__tests__"
        ]
    },
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ben-eb/cssnano.git"
    },
    "scripts": {
        "bundle-size": "webpack --json --config src/__tests__/_webpack.config.js | webpack-bundle-size-analyzer",
        "docs": "cd docs && npm run build && cd .. && gh-pages -d docs/dist",
        "prepublish": "del-cli dist && cross-env BABEL_ENV=publish babel src --out-dir dist --ignore /__tests__/",
        "pretest": "eslint --ignore-path .gitignore src",
        "report": "nyc report --reporter=html",
        "test": "nyc ava src/__tests__/*.js",
        "test-012": "nyc ava src/__tests__/*.js"
    },
    "tonicExampleFilename": "quickstart.js",
    "version": "3.10.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module cssnano](#apidoc.module.cssnano)
1.  [function <span class="apidocSignatureSpan">cssnano.</span>process (css)](#apidoc.element.cssnano.process)



# <a name="apidoc.module.cssnano"></a>[module cssnano](#apidoc.module.cssnano)

#### <a name="apidoc.element.cssnano.process"></a>[function <span class="apidocSignatureSpan">cssnano.</span>process (css)](#apidoc.element.cssnano.process)
- description and source-code
```javascript
process = function (css) {
    var options = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : {};

    options.map = options.map || (options.sourcemap ? true : null);
    return (0, _postcss2.default)([cssnano(options)]).process(css, options);
}
```
- example usage
```shell
...

};

/*
 * Compress the CSS asynchronously and log it to the console.
 */

cssnano.process(css, opts).then(result => {
    console.log(result.css);
});
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
