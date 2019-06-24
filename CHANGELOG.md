<!--
 Copyright 2019 Google LLC

 Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in
 compliance with the License. You may obtain a copy of the License at
 
        https://www.apache.org/licenses/LICENSE-2.0

 Unless required by applicable law or agreed to in writing, software distributed under the License
 is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
 implied. See the License for the specific language governing permissions and limitations under the
 License.
-->
# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unresolved]

 ### Security
 
 ### Added
  
 ### Changed
				
 ### Removed
				 
 ### Fixed

## [1.3.0] - 2019-05-24

### Security
 
### Added
 - Build step functionality for post-build actions expiring bucket lifecycle and build log upload complete
 with integration testing for all pipeline steps.
 - Pipeline model definition added in POM.
 - Automated code formatting added in POM.
  
### Changed
 - Upgraded Jenkins to 2.164.2 from 1.625.3.
 - Made UploadModule transient to satisfy JEP-200 since Jenkins was upgraded.
 