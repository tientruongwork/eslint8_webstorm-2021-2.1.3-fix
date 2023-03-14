# eslint8_webstorm-2021-2.1.3-fix

Use to fix webstorm error: 
1. **`eslint typeError: this.options.parse is not a function`**
2. **`eslint typError: this.clienginector is not a constructor`**

This `bin.zip` use to solve the problem of `eslint@^8.0.0` when working with `Jetbrains Webstorm 2.1.3`(the latest version that we could reset jetbrains evaluation license :P)

## Step by step:
1. Download and extract `bin.zip`
2. Copy and replace folder `bin` in `WebStorm 2021.1.3\plugins\JavaScriptLanguage\languageService\eslint` with extracted `bin` folder
3. Restart Webstorm
4. Enjoy !
