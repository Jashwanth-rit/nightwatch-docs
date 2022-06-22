## What is WebDriver?

<p class="whatis-logo w3c-logo"><img src="https://www.w3.org/StyleSheets/TR/2016/logos/W3C" alt="W3C WebDriver" title="W3C WebDriver" class="whatis"></p>

<p>[WebDriver][7] is a general purpose library for automating web browsers, part of the [Selenium][5] project. It is now a [W3C specification][10] which standardises browser automation, providing a reliable and consistent protocol to remotely control web browsers via a restful **HTTP API**.</p>

<p>Created more than a decade ago, **Selenium** is by far the most widely used project in the automated testing industry, providing a comprehensive set of tools for browser automation, initially written for Java but now with support for most programming languages.</p>

Internally, Nightwatch uses the [W3C WebDriver API][6] to perform the browser automation related tasks, such as opening windows or clicking links.

### Support for Selenium Grid and Cloud Providers

Nightwatch can also be used for distributed cross-browser end-to-end testing at scale together with the [Selenium Server][13] (also known as **Selenium Grid**), which is an open-source project written in Java that manages a network of WebDriver nodes.

Nightwatch also can be integrated with cloud-based testing platforms like [Browserstack][14], [SauceLabs][15], [CrossBrowserTesting][16], or [LambdaTest][17].

![Selenium Server Operation][image-2]

### Supported browsers

WebDriver is implemented by all major browser vendors as a W3C compliant HTTP service.

<table class="table table-bordered table-striped">
<thead>
 <tr>
   <th style="width: 200px;">Browser Driver</th>
   <th style="width: 100px; text-align:center">Browser</th>
   <th>Description</th>
 </tr>
</thead>
<tbody>
  <tr>
    <td><a class="local-nav" href="/gettingstarted/installation/#install-geckodriver">GeckoDriver</a></td>
    <td class="browser"><img alt="Mozilla Firefox" src="https://nightwatchjs.org/img/logos/Firefox_Logo_2017.png"/></td>
    <td>Standalone application which implements the [W3C WebDriver API](https://w3c.github.io/webdriver/#protocol) to communicate with Firefox.</td>
  </tr>

  <tr>
    <td><a class="local-nav" href="/gettingstarted/installation/#install-chromedriver">ChromeDriver</a></td>
    <td class="browser"><img alt="Google Chrome" src="https://nightwatchjs.org/img/logos/1200px-Google_Chrome_icon.svg.png"/></td>
    <td>Standalone application which implements the [W3C WebDriver API](https://w3c.github.io/webdriver/#protocol) for Chromium.<br><br>Available for Chrome on Android and Chrome on Desktop (Mac, Linux, Windows and ChromeOS).</td>
  </tr>

  <tr>
     <td><a class="local-nav" href="/gettingstarted/installation/#install-microsoftedge">Microsoft Edge Driver</a></td>
     <td class="browser"><img alt="Microsoft Edge" src="https://nightwatchjs.org/img/logos/Microsoft_Edge_logo.svg.png"/></td>
     <td>Standalone application which is used to drive the recent Edge browser, based on Chromium, which works similar to ChromeDriver.</td>
  </tr>

  <tr>
    <td><a class="local-nav" href="/gettingstarted/installation/#install-safaridriver">SafariDriver</a></td>
    <td class="browser"><img alt="Microsoft Edge" src="https://nightwatchjs.org/img/logos/safari_icon_large_2x.png"/></td>
    <td>The `/usr/bin/safaridriver` binary comes pre-installed with recent versions of Mac OS and it's available to use following the instructions on [Apple Developer website](https://developer.apple.com/documentation/webkit/testing_with_webdriver_in_safari).
    <br><br>More information is available on <a href="https://developer.apple.com/documentation/webkit/about_webdriver_for_safari" target="_blank">About WebDriver for Safari</a> page.
    </td>
  </tr>

 </tbody>
</table>

[1]:	https://nodejs.org/
[2]:	https://www.w3.org/TR/webdriver/
[3]:	https://github.com/SeleniumHQ/selenium/wiki/JsonWireProtocol
[4]:	/about
[5]:	https://selenium.dev/
[6]:	https://www.w3.org/TR/webdriver
[7]:	https://www.w3.org/TR/webdriver
[8]:	https://sites.google.com/a/chromium.org/chromedriver/
[9]:	https://github.com/mozilla/geckodriver
[10]:	https://www.w3.org/TR/webdriver/
[11]:	https://github.com/SeleniumHQ/selenium/wiki/JsonWireProtocol
[12]:	/gettingstarted/installation/#webdriver-service
[13]:	https://selenium.dev/downloads/
[14]:	https://www.browserstack.com/
[15]:	https://saucelabs.com/
[16]:	https://crossbrowsertesting.com/
[17]:   https://www.lambdatest.com/
[18]:	https://selenium.dev/downloads/
[19]:	https://selenium.dev/downloads/

[image-1]:	/img/operation.png
[image-2]:	/img/operation-cloud.png

### Recommended content
- [Selenium WebDriver Docs](https://www.selenium.dev/documentation/webdriver/)
- [WebDriver Docs on MDN](https://developer.mozilla.org/en-US/docs/Web/WebDriver)
- [W3C WebDriver spec](https://www.w3.org/TR/webdriver1/)