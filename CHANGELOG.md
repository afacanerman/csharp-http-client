# Change Log
All notable changes to this project will be documented in this file.

This project adheres to [Semantic Versioning](http://semver.org/).

## [2.0.7] - 2016-07-19
### Added
- [Pull request #11](https://github.com/sendgrid/csharp-http-client/pull/11): Adding the option to set WebProxy object to be used on HttpClient 
- Big thanks to [Juliano Nunes](https://github.com/julianonunes) for the pull request!

## [2.0.6] - 2016-07-18
### Added
- Sign assembly with a strong name

## [2.0.5] - 2016-07-14
### Fixed
- Solves [issue #7](https://github.com/sendgrid/csharp-http-client/issues/7)
- Solves [issue #256](https://github.com/sendgrid/sendgrid-csharp/issues/256) in the SendGrid C# Client
- Do not try to encode the JSON request payload by replacing single quotes with double quotes
- Updated examples and README to use JSON.NET to encode the payload
- Thanks to [Gunnar Liljas](https://github.com/gliljas) for helping identify the issue!

## [2.0.2] - 2016-06-16
### Added
- Fix async, per https://github.com/sendgrid/sendgrid-csharp/issues/235

## [2.0.1] - 2016-06-03
### Added
- Sign assembly with a strong name

## [2.0.0] - 2016-06-03
### Changed
- Made the Response variables non-redundant. e.g. response.ResponseBody becomes response.Body

## [1.0.2] - 2016-03-17
### Added
- We are live!
