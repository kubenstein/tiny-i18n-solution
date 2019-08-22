## tiny-i18n-solution

tiny-i18n-solution is a set of functions that takes care of replacing text on a page to reflect currently chosen language.

## How to use
A) Copy an paste functions into `<script>` tag

B) define i18n object with all translations in format of:
```js
var texts = {
  en: {
    title: 'EN Title'
  },
  ko: {
    title: 'KO Title',
  },
  ja: {
    title: 'JA Title',
  }
}
```

C1) Add `data-i18n='KEY'` attr with proper key to all elements you want to translate.

C2) Add `data-i18n-placeholder='KEY'` attr with proper key to all inputs you want to have their placeholders to be translated

C3) Add `data-i18n-show='LANGUAGE'` attr with proper language to all wrappers that you want to show/hide based on given language.

D) Add `data-i18n-select` attr to a select html element responsible for changing language


See [index.html](./index.html) for full example.

