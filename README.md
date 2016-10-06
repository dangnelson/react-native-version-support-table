# react-native-version-support-table
A standardized table to be added to the beginning of React Native module README files which shows the latest version number and which version of React Native, iOS, & Android it was successfully last tested on by the developer.

##Example

| Release | React Native Support | Android Support | iOS Support |
|---|---|---|---|
| 0.0.1 | 0.34.1 | 7.1 | 10.0.2 |
*Complies with [react-native-version-support-table](https://github.com/dangnelson/react-native-version-support-table)*

##What this solves
Help solves the problem many developers face when starting new React Native projects with multiple modules where build and or usage errors occur. Makes troubleshooting / choosing versions a more transparent process.

Saves module developers the headache of additional repository issues being created because new versions aren't yet supported.

##Usage

###Placement

Add before your first H1 header. This allows for developers to see whether or not your module is compatiable with their app before diving into your documentation.

###Markdown
Copy this Markdown and add it to the beginning of your README file before the first header.
```
| Release | React Native Support | Android Support | iOS Support |
|---|---|---|---|
| 0.0.1 | 0.34.1 | 7.1 | 10.0.2 |
*Complies with [react-native-version-support-table](https://github.com/dangnelson/react-native-version-support-table)*
```

###iOS / Android Only
Use "NONE" in place of version number.

Example:

| Release | React Native Support | Android Support | iOS Support |
|---|---|---|---|
| 0.0.1 | 0.34.1 | NONE | 10.0.2 |
*Complies with [react-native-version-support-table](https://github.com/dangnelson/react-native-version-support-table)*

###Multiple Versions
Add multiple rows to show versions successfully tested across additional Operating System or React Native versions.

Example: 

| Release | React Native Support | Android Support | iOS Support |
|---|---|---|---|
| 1.0.0 | 0.34.1 | 7.1 | 10.0.2 |
| 0.9.2 | 0.33.0 | 7.1 | 10.0.2 |
*Complies with [react-native-version-support-table](https://github.com/dangnelson/react-native-version-support-table)*

##Modules Currently Supporting This Standard
