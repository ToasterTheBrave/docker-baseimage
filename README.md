# Overview
This is a base image built from alpine, making it incredibly small.  There are additional decisions made for default software that increased this to 17.29 MB in size total.

##### Additions on top of alpine base:
* Updated apk
* Added and updated CA certificates
* Installed Bash
* Installed Dockerize
* Created /app dir

# Usage
This is meant to be used as a base for other docker images in the Dockerfile

# License and Author
Author: Tyler Ruppert

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0
Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.