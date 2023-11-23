## 3.0.2 - 23/11/2023
### What's Changed
* Feature/adjust padding around slider by @ChrisElliotUK in https://github.com/loonix/another_xlider/pull/29
* add typing by @ChrisElliotUK in https://github.com/loonix/another_xlider/pull/28
* undo typing by @ChrisElliotUK in https://github.com/loonix/another_xlider/pull/30
* Handle null animation or controller in _stopHandlerAnimation function by @john-paradym in https://github.com/loonix/another_xlider/pull/32

### New Contributors
* @ChrisElliotUK made their first contribution in https://github.com/loonix/another_xlider/pull/29
* @john-paradym made their first contribution in https://github.com/loonix/another_xlider/pull/32

**Full Changelog**: https://github.com/loonix/another_xlider/compare/3.0.1...3.0.2

## 3.0.1 - 29/03/2023
- fix: selectByTap doesn't work by actual Android devices - thanks to @YasufumiMuranaka
- kotlin_version is now '1.6.0'
- compileSdkVersion requires version 31
- replaced lint plugin and rules

## 3.0.0 - 21/03/2023
Restructured the code to make it more readable, fixed documentation and flutter 3 requirements.
Also separated classes and enums to its own files.

### BREAKING CHANGES
* Refactored the classes and widgets to its own folders to have better readability of the core code
This means you are now able to just import the classes you actually use
## 1.1.2 - 18/07/2022
Fixes the issue with flutter 3.X widget binding '?'
## 1.1.1 - 29/06/2022
Bugfix to WidgetsBinding -> https://github.com/loonix/another_xlider/issues/12 flagged by @greyovo
## 1.1.0 - 21/05/2022 (Flutter 3 upgrade)

### What's Changed
* feat: flutter 3 support by @erknvl in https://github.com/loonix/another_xlider/pull/10

### New Contributors
* @erknvl made their first contribution in https://github.com/loonix/another_xlider/pull/10

**Full Changelog**: https://github.com/loonix/another_xlider/compare/1.0.1...1.1.0

## [1.0.1+2] - 14/02/2022

Big thanks to @felixgabler for finding and fixing the following bugs:

* Prevent exception by checking mounted state before post frame callback
* Adjust handler placement after tap
* Make it possible to specify how many small lines should be between big lines

## [1.0.0] - 24/06/2021

* Null safety upgrade
  1
