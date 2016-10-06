# react-native-version-support-table
A standarized table to be added to the beginning of React-Native module README files which shows the latest version number and which version of React Native, iOS, & Android it was successfully last tested on by the developer.

##Example

| Latest Release | React Native Support | Android Support | iOS Support |
|---|---|---|---|
| 0.0.1 | 0.34.1 | 7.1 | 10.0.2 |
*Complies with [react-native-version-support-table](https://github.com/dangnelson/react-native-version-support-table)*

##What this solves
Solves the problem many developers face when starting new RN projects with multiple modules and facing build / usage errors.

Saves module developers the headache of additional issues being created because they don't yet support new versions.

##Markdown
Copy this Markdown and add it to the beginning of your README file before the first header.
```
| Latest Release | React Native Support | Android Support | iOS Support |
|---|---|---|---|
| 0.0.1 | 0.34.1 | 7.1 | 10.0.2 |
*Complies with [react-native-version-support-table](https://github.com/dangnelson/react-native-version-support-table)*
```

##iOS / Android Only
Use "NONE" in place of version number.

Example:

| Latest Release | React Native Support | Android Support | iOS Support |
|---|---|---|---|
| 0.0.1 | 0.34.1 | NONE | 10.0.2 |
*Complies with [react-native-version-support-table](https://github.com/dangnelson/react-native-version-support-table)*
