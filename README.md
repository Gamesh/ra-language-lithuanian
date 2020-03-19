# Lithuanian Messages for React-Admin

[![npm ra-language-lithuanian](https://img.shields.io/npm/v/ra-language-lithuanian.svg)](https://npmjs.org/package/ra-language-lithuanian)
[![npm downloads](https://img.shields.io/npm/dm/ra-language-lithuanian.svg)](https://www.npmjs.com/package/ra-language-lithuanian)
[![npm bundle size](https://img.shields.io/bundlephobia/minzip/ra-language-lithuanian.svg)](https://bundlephobia.com/result?p=ra-language-lithuanian)

Lithuanian messages for [react-admin](https://github.com/marmelab/react-admin), the frontend framework for building admin applications on top of REST/GraphQL services.

## Installation

```sh
npm install --save ra-language-lithuanian
```

## Usage

```js
import lithuanianMessages from 'ra-language-lithuanian';
import polyglotI18nProvider from 'ra-i18n-polyglot';

const messages = {
    'lt': lithuanianMessages,
};
const i18nProvider = polyglotI18nProvider(locale => messages[locale]);

<Admin locale="lt" i18nProvider={i18nProvider}>
  ...
</Admin>
```

## License

This translation is licensed under the [MIT Licence](LICENSE).
