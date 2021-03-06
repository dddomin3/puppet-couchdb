# couchdb module for puppet

This module manages couchdb on Linux (RedHat/Debian) distros.

## Installation & Dependencies

This forked module does not require [metcalfc/rpmrepos](https://forge.puppetlabs.com/metcalfc/rpmrepos)

To install the module with its required dependencies issue the following: 
```
puppet module install jonbrouse/couchdb
```
## Description

This module installs couchdb and populates local.ini.erb with the defaults set in couchdb::params

## Usage

### couchdb
Installs the couchdb package.

    class { 'couchdb': }

## License
```
Author:: Jon Brouse (<jbrouse19@gmail.com>)
Copyright:: Copyright (c) 2013 Jon Brouse
License:: Apache License, Version 2.0

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0


Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
