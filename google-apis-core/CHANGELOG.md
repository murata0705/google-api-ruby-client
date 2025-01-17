# Release History

### 0.8.0 (2022-09-16)

#### Features

* Add storage upload to move away from unified upload protocol ([#11508](https://github.com/googleapis/google-api-ruby-client/issues/11508)) 

### 0.7.2 (2022-09-15)

#### Bug Fixes

* do not reset query_values in case of form encoding ([#11654](https://github.com/googleapis/google-api-ruby-client/issues/11654)) 

### 0.7.1 (2022-09-14)

#### Bug Fixes

* Revert "chore(core): log errors as error instead of debug([#6494](https://github.com/googleapis/google-api-ruby-client/issues/6494))" ([#11561](https://github.com/googleapis/google-api-ruby-client/issues/11561)) 

### 0.7.0 (2022-06-30)

#### Features

* Add storage specific download to respond with http header 

### 0.6.0 (2022-06-15)

#### Features

* add few more errors as retriable errors

### 0.5.0 (2022-05-15)

#### Features

* Add support for retry options to be configurable

### 0.4.2 (2022-01-21)

#### Bug Fixes

* Support for max elapsed time configuration.

### 0.4.1 (2021-07-19)

* FIX: Prevent duplicated pagination when a response returns an empty string as the next page token.

### 0.4.0 (2021-06-28)

* Expanded googleauth dependency to include future 1.x versions

### 0.3.0 (2021-03-07)

#### Features

* Drop support for Ruby 2.4 and add support for Ruby 3.0

### 0.2.1 (2021-01-25)

#### Bug Fixes

* Add webrick to the gem dependencies, for Ruby 3 compatibility

### 0.2.0 (2021-01-06)

* Munge reported client version so backends can recognize split clients

### 0.1.0 (2021-01-01)

* Initial release, extracted from google-api-client.
