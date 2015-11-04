polymer-cordova-network-activity [![Bower version](https://badge.fury.io/bo/polymer-cordova-network-activity.svg)](http://badge.fury.io/bo/polymer-cordova-network-activity)
=========

Web component to control Network Activity Indicator via Cordova plugin. The web component is built with [Polymer 1.x](https://www.polymer-project.org).

You need to install the Cordova plugin [cordova-plugin-networkactivityindicator](https://github.com/ohh2ahh/NetworkActivityIndicator) to use this Polymer component.


## Usage

`bower install polymer-cordova-network-activity`

```html
<polymer-cordova-network-activity visible={{loading}}></polymer-cordova-network-activity>
```


## Properties

These properties are available for `polymer-cordova-network-activity`:

Property    | Type    | Description
----------- | ------- | ----------------------------
**visible** | Boolean | Flag if the network activity indicator is currently shown


## Methods

These methods are available for `polymer-cordova-network-activity`:

Method   | Description
-------- | ----------------------------
**show** | Shows the network activity indicator
**hide** | Hides the network activity indicator


## License

    This software is licensed under the Apache 2 license, quoted below.

    Copyright 2011-2015 Collaborne B.V. <http://github.com/Collaborne/>

    Licensed under the Apache License, Version 2.0 (the "License"); you may not
    use this file except in compliance with the License. You may obtain a copy of
    the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
    WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
    License for the specific language governing permissions and limitations under
    the License.
    