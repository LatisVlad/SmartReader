# Changelog
All notable changes to this project will be documented in this file.

## 0.6.3
- Fixed [issue #11](https://github.com/Strumenta/SmartReader/issues/11)

## 0.6.2
- Fixed [issue #9](https://github.com/Strumenta/SmartReader/issues/9)
- Added Readability update to transform lazy images
- Added Readability update regarding share elements

## 0.6.1
- Fixed bug in dependency listing for the nuget package

## 0.6.0
- Updated AngleSharp dependency. Now the minimum version is .NETStandard 2.0 (this is because of AngleSharp.Css)
- Added improvements from latest updates of Readability
- Fixed bug for property recognition
- Changed minimum time to read from 0 to 1 minute
- Improved tests

## 0.5.2 - 2019/01/12
- Added metadata for site name
- Fixed bugs for recognition of title and author metadata
- Added improvements from latest updates of Readability
- Improved documentation

## 0.5.1 - 2018/08/27
- Added support for custom operations before processing
- Added fix to preserve CSS classes when removing a DIV with only one P
- Improved testing
- Added improvements from August updates of Readability

## 0.5.0 - 2018/08/13
- Added support for custom operations (Thanks to [G�bor Gergely](https://github.com/kodfodrasz)
- Added support to modify regular expressions used to determine what is part of the article and what is discarded (Thanks to [G�bor Gergely](https://github.com/kodfodrasz)
- Added improvements from latest updates of Readability

## 0.4.0 - 2018/04/01
- Fixed [issue #7](https://github.com/Strumenta/SmartReader/issues/7)
- Added support to attribute xml:lang for language detection (Thanks to [G�bor Gergely](https://github.com/kodfodrasz))
- Added new test pages for language detection
- Added improvements from March updates of Readability

## 0.3.1 - 2018/03/03
- Fixed [issue #5](https://github.com/Strumenta/SmartReader/issues/5)
- Added improvements from February updates of Readability
- Added new test page
- Fixed comparison bugs in readability scores

## 0.3.0 - 2018/02/17 
- Cleanup of the code and naming issues (Thanks to [jamie-lord](https://github.com/jamie-lord))
- Improved testing
- Added improvement from January update of Readability
- Fixed bug for the detection of the readability of article
- Fixed bug for the fixing of relative URIs
- Fixed bug in elimination of certain nodes
- Added detection of featured image and images found in the article

## 0.2.0 - 2018/01/15
- Added improvements from December updates of Readability
- Solved [issue #2](https://github.com/Strumenta/SmartReader/issues/2) (Thanks to [Yasindn](https://github.com/yasindn))
- Breaking Changes to the API method names to improve clarity and solve issue #2. The Parse() method is now private, so if you were using it, now instead you should use the GetArticle/GetArticleAsync method. If you were using the ParseArticle method you can keep using it or choose the async version: ParseArticleAsync.
- Merged pull-request #3 for the caching of HttpClient (Thanks to [DanRigby](https://github.com/DanRigby))

## 0.1.3 - 2017/11/27
- Added improvements from November updates of Readability
- Added reading of itemprop properties for metadata extraction
- Integrated tests from Readability

## 0.1.2 - 2017/10/17

- Improved the accuracy of the calculation for reading time

## 0.1.1 - 2017/09/26

- Release based on September updates of Readability.

## 0.1.0 - 2017/08/09

- Initial release, based on a February release of Readability.