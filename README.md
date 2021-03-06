# Parse Facebook Utils for Android
[![Build Status][build-status-svg]][build-status-link]
[![Coverage Status][coverage-status-svg]][coverage-status-link]
[![Maven Central][maven-svg]][maven-link]
[![License][license-svg]][license-link]

A utility library to authenticate `ParseUser`s with the Facebook SDK. For more information, see our [guide][guide].

## Download
Download [the latest JAR][latest] or define in Gradle:

```groovy
dependencies {
  compile 'com.parse:parsefacebookutils-v4-android:1.10.4@aar'
}
```

Snapshots of the development version are available in [Sonatype's `snapshots` repository][snap].

## Usage
Everything can done through the supplied gradle wrapper:

### Compile a JAR
```
./gradlew clean jarRelease
```
Outputs can be found in `Parse/build/libs/`

### Run the Tests
```
./gradlew clean testDebug
```
Results can be found in `Parse/build/reports/`

### Get Code Coverage Reports
```
./gradlew clean jacocoTestReport
```
Results can be found in `Parse/build/reports/`

## How Do I Contribute?
We want to make contributing to this project as easy and transparent as possible. Please refer to the [Contribution Guidelines](CONTRIBUTING.md).

## License
    Copyright (c) 2015-present, Parse, LLC.
    All rights reserved.

    This source code is licensed under the BSD-style license found in the
    LICENSE file in the root directory of this source tree. An additional grant 
    of patent rights can be found in the PATENTS file in the same directory.

As of April 5, 2017, Parse, LLC has transferred this code to the parse-community organization, and will no longer be contributing to or distributing this code. 

 [guide]: https://parse.com/docs/android/guide#users-facebook-users

 [latest]: https://search.maven.org/remote_content?g=com.parse&a=parsefacebookutils-v4-android&v=LATEST
 [snap]: https://oss.sonatype.org/content/repositories/snapshots/

 [build-status-svg]: https://travis-ci.org/ParsePlatform/ParseFacebookUtils-Android.svg?branch=master
 [build-status-link]: https://travis-ci.org/ParsePlatform/ParseFacebookUtils-Android
 [coverage-status-svg]: https://coveralls.io/repos/ParsePlatform/ParseFacebookUtils-Android/badge.svg?branch=master&service=github
 [coverage-status-link]: https://coveralls.io/github/ParsePlatform/ParseFacebookUtils-Android?branch=master
 [maven-svg]: https://maven-badges.herokuapp.com/maven-central/com.parse/parsefacebookutils-v4-android/badge.svg?style=flat
 [maven-link]: https://maven-badges.herokuapp.com/maven-central/com.parse/parsefacebookutils-v4-android
 [license-svg]: https://img.shields.io/badge/license-BSD-lightgrey.svg
 [license-link]: https://github.com/ParsePlatform/ParseFacebookUtils-Android/blob/master/LICENSE
