# Vue language automatic text replacement for i18n translation
<b>Automate replacing of text in your editor and scripts for language translation using vue-i18n extension</b>

An extension that will automate the steps of extacting out all the text appearing on the page and adding these to the `en.json file` then replacing the text on the page with the equivalent code required with the vue-i18n extension.
## Features

- Highlight text to translate
- Invoke the extension (`ctrl+shift+p Extract translation`, or using shortcut keys `alt+t`)
- Text extracted and inserted into en.json file by default
- Text replaced on the page with equivalent code that uses vue-i18n extension format.

> Default path to locales folder containing en.json is `<root folder>\src\locales`. This can be overriden under the setting: `dnv.translation.localespath`

<!--todo insert image here-->

## Requirements
- vue-i18n installed
- `locales` folder under the root folder
## Known Issues

- Text replacement in the html inserts curly braces when these not required

## Release Notes



### 0.0.1

Initial release of language translation utility


-----------------------------------------------------------------------------------------------------------

