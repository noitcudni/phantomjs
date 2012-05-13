<div style="background-color:#F1F4F6; border: 1px solid #DEE4EC; width: 80%; margin: 15px auto; padding: 10px;">
This fork of PhantomJS was developed specifically for <a href="http://packershack.com">PackerShack.com</a>, a hostel aggregator. I needed a way for phantomjs to ignore a specific set of resources (for instance, css, js, png, gif, etc.) in order to speed up scraping. With this fork, one can tell phantomjs to ignore resources by passing in a set of regular expressions. For example, --ignore-resources=".*?.css|.*?.png".
</div>

# [PhantomJS](http://phantomjs.org) - Scriptable Headless WebKit

PhantomJS ([www.phantomjs.org](http://phantomjs.org)) is a headless WebKit scriptable with JavaScript or CoffeeScript. It is used by hundreds of [developers](http://code.google.com/p/phantomjs/wiki/ExternalArticles) and dozens of [organizations](http://code.google.com/p/phantomjs/wiki/WhoUsesPhantomJS) for web-related development workflow.

The latest [stable release](http://code.google.com/p/phantomjs/wiki/ReleaseNotes) is version 1.5 (codenamed "Ghost Flower"). Follow the official Twitter stream [@HeadlessPhantom](http://twitter.com/HeadlessPhantom) to get the frequent development updates.

PhantomJS is created and maintained by [Ariya Hidayat](http://ariya.ofilabs.com/about) (Twitter: [@ariyahidayat](http://twitter.com/ariyahidayat)), with the help of [many contributors](https://github.com/ariya/phantomjs/contributors).

## Use Cases

- **Headless web testing**. Lightning-fast testing without the browser is now possible! Various [test frameworks](http://code.google.com/p/phantomjs/wiki/TestFrameworkIntegration) such as Jasmine, Capybara, QUnit,  WebDriver, YUI Test, BusterJS, FuncUnit, Robot Framework, and many others are supported.

- **Site scraping**. [Access and manipulate](http://code.google.com/p/phantomjs/wiki/QuickStart#DOM_Manipulation) webpages with the standard DOM API, or with usual libraries like jQuery.

- **Page rendering**. [Capture](http://code.google.com/p/phantomjs/wiki/QuickStart#Rendering) the full contents, even with SVG and Canvas, to an image. Build server-side web graphics apps, from a screenshot service to a vector chart rasterizer.

- **Network monitoring**. [Monitor](http://code.google.com/p/phantomjs/wiki/QuickStart#Network_traffic) network activity, track resource loading, perform load-balancing tests, verify contents optimization, and many others.

## Features

- **Multiplatform**, available on major operating systems: Windows, Mac OS X, Linux, other Unices.
- **Fast and native implementation** of web standards: DOM, CSS, JavaScript, Canvas, SVG. No emulation!
- **Pure headless (X11) on Linux**, ideal for continuous integration systems. Also runs on Amazon EC2.
- **Easy to install**: [Download](http://code.google.com/p/phantomjs/wiki/Installation), unpack, and start having fun in just 5 minutes.

## Ecosystem

PhantomJS needs not be used only as a stand-alone tool. Check also some excellent related projects:

- [CasperJS](http://casperjs.org) enables easy navigation scripting and common high-level testing.
- [Poltergeist](https://github.com/jonleighton/poltergeist) allows running Capybara tests headlessly.
- [Guard::Jasmine](https://github.com/netzpirat/guard-jasmine) automatically tests Jasmine specs on Rails when files are modified.
- [GhostDriver](http://detro.github.com/ghostdriver/) complements Selenium tests with a PhantomJS WebDriver implementation.
- [PhantomRobot](https://github.com/datakurre/phantomrobot) runs Robot Framework acceptance tests in the background via PhantomJS.

and many others [companion projects](http://code.google.com/p/phantomjs/wiki/WhoUsesPhantomJS).

## Questions?

- Explore the complete [documentation](http://code.google.com/p/phantomjs/wiki/PhantomJS?tm=6).
- Read tons of [user articles](http://code.google.com/p/phantomjs/wiki/ExternalArticles) on using PhantomJS.
- Join the [mailing-list](http://groups.google.com/group/phantomjs) and discuss with other PhantomJS fans.
