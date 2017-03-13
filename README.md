# Japanese Translations for Admin-on-rest

Japanese translations for [admin-on-rest](https://github.com/marmelab/admin-on-rest), the frontend framework for building admin applications on top of REST services.

## Installation

```sh
npm install --save aor-language-japanese
```

## Usage

```js
import japaneseMessages from 'aor-language-japanese';

const messages = {
    'ja': japaneseMessages,
};

<Admin locale="ja" messages={messages}>
  ...
</Admin>
```

## License

This translation is licensed under the [MIT Licence](LICENSE).
