# appium_ruby_test

## Running Automated Website Tests for Desktop and Virtual Mobile Native Browsers
https://wiki.saucelabs.com/display/DOCS/Running+Automated+Website+Tests+for+Desktop+and+Virtual+Mobile+Native+Browsers
1. Set up your test to connect to the Sauce Labs browser cloud using your account credentials.
1. Use the [Platform Configurator](https://wiki.saucelabs.com/display/DOCS/Platform+Configurator#/) to get the Desired Capabilities of your test.
   1. Ruby Example:
    ```ruby
    caps = Selenium::WebDriver::Remote::Capabilities.iphone()
    caps['appiumVersion'] = '1.7.1'
    caps['deviceName'] = 'iPad Pro Simulator'
    caps['deviceOrientation'] = 'portrait'
    caps['platformVersion'] = '9.3'
    caps['platformName'] = 'iOS'
    caps['browserName'] = ''
    ```
