# rainy
What's the weather? Aesthetic and minimalistic weather fetching tool.

<img src="assets/preview.png">

## Dependencies
* ```python```
* ```requests```
* ```make```

You can install all of them from your distros repositories (usually they're named ```python```, ```python-requests``` and ```make```)

## Installation & Configuration
To install rainy, clone or download the repo, ```cd``` into it and just run ```make install``` (you can run ```make uninstall``` to uninstall it)

**Before usage, you need to configure it**

* First create an [OpenWeatherMap](https://home.openweathermap.org/users/sign_up) account, go to [API keys](https://home.openweathermap.org/api_keys) and get your key.
* Then edit ```/usr/local/bin/rainy``` and set the API key, city and timezone in the config section.

## Usage
When set up correctly, you can just go to your terminal and type ```rainy```
If you like this tool, please consider starring as it helps the growth <3

### Thanks
* [wego](https://github.com/schachmat/wego) for providing ASCII weather icons
