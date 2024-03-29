# Changelog

These are the changes to each version that have been released
on the official Visual Studio extension gallery.

## 2.5

**2022-09-22**

- Disambiguate setInterval.  Previously VS could get confused if there was anything node-related in the vicinity of the project, and refuse to compile because it thought we were using a node function.
- Run code through Prettier so the [TypeScript Analyzer](https://marketplace.visualstudio.com/items?itemName=RichNewman.TypeScriptAnalyzerEslintPrettier2019) doesn't show warnings.
- Update text on [Marketplace entry](https://marketplace.visualstudio.com/items?itemName=Rich-Newman.TypeScriptHTMLApplicationTemplate) on release to reference the new version of this extension for [Visual Studio 2022](https://marketplace.visualstudio.com/items?itemName=Rich-Newman.TypeScriptHTMLApplicationTemplate2022)

## 2.4

**2022-09-01**

- Previous release not tested adequately: rolling back to v2.1.

## 2.3

**2022-09-01**

- Disambiguate setInterval.  Previously VS could get confused if there was anything node-related in the vicinity of the project, and refuse to compile because it thought we were using a node function.

## 2.2

**2022-09-01**

- Upgraded to work in Visual Studio 2022 as well as Visual Studio 2017 and Visual Studio 2019.

## 2.1

**2021-03-24**

- Uses latest available version of TypeScript, rather than using 2.1 and asking for an upgrade every time
- Better descriptions, making it clearer what this is.  Previous descriptions referred prominently to Visual Studio 2015, which doesn't make much sense in 2021.
- Update code so it lints with TypeScript Analyzer.

## 2.0

**2019-06-01**

- Make available in Visual Studio 2019

## 1.0

**2017-05-09**

- Initial upgraded version of TypeScript HTML Application Template