# gitserver
This is a generate purpose REST API for interfacing with Git.

This Dart package is automatically generated by the [OpenAPI Generator](https://openapi-generator.tech) project:

- API version: 0.0.1
- Build package: org.openapitools.codegen.languages.DartClientCodegen
For more information, please visit [http://drdgvhbh.io](http://drdgvhbh.io)

## Requirements

Dart 1.20.0 or later OR Flutter 0.0.20 or later

## Installation & Usage

### Github
If this Dart package is published to Github, please include the following in pubspec.yaml
```
name: gitserver
version: 1.0.0
description: OpenAPI API client
dependencies:
  gitserver:
    git: https://github.com/GIT_USER_ID/GIT_REPO_ID.git
      version: 'any'
```

### Local
To use the package in your local drive, please include the following in pubspec.yaml
```
dependencies:
  gitserver:
    path: /path/to/gitserver
```

## Tests

TODO

## Getting Started

Please follow the [installation procedure](#installation--usage) and then run the following:

```dart
import 'package:gitserver/api.dart';

// TODO Configure API key authorization: api_key
//defaultApiClient.getAuthentication<ApiKeyAuth>('api_key').apiKey = 'YOUR_API_KEY';
// uncomment below to setup prefix (e.g. Bearer) for API key, if needed
//defaultApiClient.getAuthentication<ApiKeyAuth>('api_key').apiKeyPrefix = 'Bearer';

var api_instance = new DefaultApi();
var directory = directory_example; // String | The directory of the repository

try {
    var result = api_instance.listCommits(directory);
    print(result);
} catch (e) {
    print("Exception when calling DefaultApi->listCommits: $e\n");
}

```

## Documentation for API Endpoints

All URIs are relative to *http://localhost/v1*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*DefaultApi* | [**listCommits**](docs//DefaultApi.md#listcommits) | **GET** /repositories/{directory}/commits | List commits


## Documentation For Models

 - [Contributor](docs//Contributor.md)
 - [InlineResponse200](docs//InlineResponse200.md)
 - [LogData](docs//LogData.md)


## Documentation For Authorization


## api_key

- **Type**: API key
- **API key parameter name**: Authorization
- **Location**: HTTP header


## Author

ryanleecode@gmail.com


