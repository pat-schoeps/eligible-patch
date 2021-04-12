# Changelog
## 2.9.11 - 2021-04-01
  - Updated pinned GDS SSL certificate

## 2.9.10 - 2020-05-13
  - Updated pinned GDS SSL certificate

## 2.9.9 - 2019-08-07
  - Added Icd code endpoints

## 2.9.8 - 2019-06-24
  - Added an endpoint to fetch Risk Assessment

## 2.9.7 - 2019-03-08
  - Updated GDS SSL certificate

## 2.9.6 - 2018-07-17
  - Added Risk Assessment endpoints

## 2.9.5 - 2018-07-06
  - Added Mix and Match support for coverage requests

## 2.9.4 - 2018-04-25
  - Rename endpoint provider_detail to provider_model

## 2.9.3 - 2018-04-19
  - Added new endpoints visit types, provider details

## 2.9.2 - 2018-03-26
  - We can use session token or api_key for making a Eligible Call
  - for session token supported endpoints

## 2.9.0 - 2017-10-04
  - Adding revoke functionality for session tokens

## 2.8.2 - 2017-03-24
  - Upgraded internal rest-client dependency to 2.0.0 and higher

## 2.8.1 - 2017-02-23
  - Upgraded internal rest-client dependency to 2.0.1
  - Fixes mime-type dependency issue with newer Rails projects

## 2.8.0 - 2017-02-23
  - Added support for session tokens

## 2.7.0 - 2016-12-14
  - Changed default content type to application/json

## 2.6.3 - 2016-11-18
  - Added a new certificate fingerprint

## 2.6.2 - 2016-08-31
  - New APIs added in testing mode, no public-facing changes

## 2.6.1 - 2016-05-10
  - Suppressing ssl_verify_callback return code warning
  - Added new endpoints: received_pdf, precert and referral
  - Refactored the code and fixed couple of bugs
  - Documentation updates for the endpoints

## 2.6.0 - 2016-02-23
  - Added new endpoints customer, original signature pdf and payer.
  - Added specs
  - Bumped api version to 1.5
  - Fixed few bugs

## 2.5.0 - 2016-01-07
  - Added certificate pinning
  - Added rubocop and fixed style/linting/metrics issues
  - Migrated from outdated test-unit/mocha to current rspec for test suite

## 2.4
  - Refactoring Code
  - More test cases
  - Removed legacy endpoint for *plans*, *coverage* should be used instead.
  - Removed legacy endpoint for *services*, *coverage* should be used instead.
  - List of contributors and documentation updated.
  - Gemfile updated, dependencies updated as well.
  - Removed json gem in favor of multi_json
  - Fixed the code to let the users make x12 requests at anytime.
  - New endpoint for Tickets

## 2.3
  - New endpoint for Batch

## 2.2
  - New endpoint for x12 POST

## 2.1
  - New endpoint for payment status

## 2.0
  - Additional endpoints for claims, enrollments, and coverage

## 1.1
  - Additional endpoints for service/general and service/list
  - Support x12 format in params

## 1.0
  - Initial release
