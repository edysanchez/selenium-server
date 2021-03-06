Selenium server standalone
===============

This repository allows you to have the latest stable version of Selenium server integrated into your projects.
Selenium server standalone is a browser automation framework. We will maintain the repository updated with the latest stable version of Selenium.

Instructions:
-------------

1. Add the following line to your composer.json configuration file: ```"emagister/selenium-server": "2.*"```. It should look like this:
```json
{
        "config": {
            "bin-dir": "bin/"
        },
        "minimum-stability": "stable",
        "require": {
            "emagister/selenium-server": "2.*"
        }
}
```

2. Execute the following command in the home directory of your project: ```php composer.phar install```

3. And you're ready to go! Now you can launch the selenium server from the corresponding directory (in this case "bin"): ```java -jar bin/selenium-server.jar```
Chrome Driver:
______________
add the following arguments when running the selenium server.
-Dwebdriver.chrome.driver="bin/chromedriver" -browser "browserName=chrome,version=17" 


