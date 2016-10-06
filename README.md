# react-native-version-support-table
A standardized table to be added to the beginning of React Native component README files which shows the latest version number and which version of React Native, iOS, & Android it was successfully last tested on by the developer.

##Example

| Version | React Native Support | Android Support | iOS Support |
|---|---|---|---|
| 0.0.1 | 0.34.1 | 7.1 | 10.0.2 |
*Complies with [react-native-version-support-table](https://github.com/dangnelson/react-native-version-support-table)*

##What this solves
Help solves the problem many developers face when starting new React Native projects with multiple components where build and or usage errors occur. Makes troubleshooting / choosing versions a more transparent process.

Saves component developers the headache of additional repository issues being created because new versions aren't yet supported.

##Usage

###Placement

Add before your first H1 header. This allows for developers to see whether or not your component is compatiable with their app before diving into your documentation.

###Markdown
Copy this Markdown and add it to the beginning of your README file before the first header. Change the version numbers to the latest you've tested your component on.
```
| Version | React Native Support | Android Support | iOS Support |
|---|---|---|---|
| 0.0.1 | 0.34.1 | 7.1 | 10.0.2 |
*Complies with [react-native-version-support-table](https://github.com/dangnelson/react-native-version-support-table)*
```

###iOS / Android Only
Use "NONE" in place of version number.

Example:

| Version | React Native Support | Android Support | iOS Support |
|---|---|---|---|
| 0.0.1 | 0.34.1 | NONE | 10.0.2 |
*Complies with [react-native-version-support-table](https://github.com/dangnelson/react-native-version-support-table)*

###Multiple Versions
Add multiple rows to show component versions successfully tested across additional Operating System or React Native versions. This should be used when there's a breaking change that doesn't allow the latest version of your component to support older verisons of React Native or Android / iOS. Links to seperate README files are recommended if documentation has changed between versions.

Example: 

| Version | React Native Support | Android Support | iOS Support | Documentation |
|---|---|---|---|---|
| 1.0.0 | 0.34.1 | 7.1 | 10.0.2 | [README]() |
| 0.9.2 | 0.33.0 | 7.1 | 10.0.2 | [README]() |
*Complies with [react-native-version-support-table](https://github.com/dangnelson/react-native-version-support-table)*

##Components Currently Supporting This Standard

NONE YET

Please add a New Issue if there's a component you know of using this standard that's not on the list.
