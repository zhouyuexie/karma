# Karma
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/karma-runner/karma) [![npm version](https://img.shields.io/npm/v/karma.svg?style=flat-square)](https://www.npmjs.com/package/karma) [![npm downloads](https://img.shields.io/npm/dm/karma.svg?style=flat-square)](https://www.npmjs.com/package/karma)

[![Build Status](https://img.shields.io/travis/karma-runner/karma/master.svg?style=flat-square)](https://travis-ci.org/karma-runner/karma) [![Build Status](https://img.shields.io/appveyor/ci/dignifiedquire/karma/master.svg?style=flat-square)](https://ci.appveyor.com/project/dignifiedquire/karma) [![Code Climate](https://img.shields.io/codeclimate/github/karma-runner/karma.svg?style=flat-square)](https://codeclimate.com/github/karma-runner/karma) [![PRs Welcome](https://img.shields.io/badge/prs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com) [![Dependency Status](https://img.shields.io/david/karma-runner/karma.svg?style=flat-square)](https://david-dm.org/karma-runner/karma) [![devDependency Status](https://img.shields.io/david/dev/karma-runner/karma.svg?style=flat-square)](https://david-dm.org/karma-runner/karma#info=devDependencies)

一个简单的工具，可以让你在多个_真实_的浏览器执行JavaScript代码。

> Karma 的主要目的是让你测试开发驱动：简单、快速、有趣。


## 帮助和支持.

> 对于问题和支持，请使用邮件列表或Gitter。这些问题跟踪是针对错误报告和功能讨论。

* Obligatory [documentation]
* Quick questions:
[![Gitter Chat](https://img.shields.io/badge/GITTER-join%20chat-green.svg?style=flat-square)](https://gitter.im/karma-runner/karma)
* Longer questions: [Mailing List]
* Bug reports [Issue Tracker]
* Everything less than 140 characters: [@JsKarma] on Twitter



## 我应该什么时候使用 Karma?

* 你想在真正的浏览器中测试代码。
* 您想在多个浏览器（桌面、移动、平板电脑等）测试代码。
* 您希望在开发过程中执行您的测试。
* 您想在一个连续的集成服务器上执行测试。
* 你想子在执行你的测试中保存每一个测试。
* 你热爱终端。
* 不希望你的生活被测试占据。
* 你希望使用 [Istanbul] 自动生成覆盖报告。
* 你希望对你的文件使用 [RequireJS] 。


## 但是我还想使用 \_insert testing library\_

Karma 不是一个测试框架，也不是一个断言库。Karma 只是启动一个HTTP服务器，并生成测试HTML文件，您可能已经知道如何使用你最喜爱的框架进行测试，因此，为了测试的目的，你可以使用几乎你喜欢的任何东西。已经有大多数常见的测试框架的插件：

* [Jasmine]
* [Mocha]
* [QUnit]
* and [many others](https://www.npmjs.org/browse/keyword/karma-adapter)

如果你找不到你最喜欢的框架的一个适配器，不要担心，你可以自己写，这不是很难，我们在这里提供帮助。


## 我可以使用哪个浏览器？

所有主要的浏览器都支持，如果你想知道更多的浏览器[browsers]页面。


## 故障排除.
See [FAQ](https://karma-runner.github.io/latest/intro/faq.html).


## 我想用它需要在哪里签名？

你不需要签署任何东西，这里有一些资源来帮助你开始…


### 必须的视频.

每一个重大的项目有一个视频，所以这是我们的视频。只要点击 [here] ，让它开始。


### 安装.

看这里 [installation](https://karma-runner.github.io/latest/intro/installation.html).


### 使用它.

See [configuration](https://karma-runner.github.io/latest/intro/configuration.html).


## 这个非常好，我希望帮助.

请看这里
[contributing](https://karma-runner.github.io/latest/dev/contributing.html).


## 你为什么要创建这个？

纵观 [AngularJS]的发展，我们一直在使用 [JSTD] 测试。我真的觉得 [JSTD] 是一个伟大的想法。不幸的是，我们已经有关于 [JSTD] 的很多问题，所以我们决定将基于同样的想法创建我们自己的测试工具。我们想要一个简单的工具只是执行JavaScript测试，既稳定又快速。这就是为什么我们使用非常棒的 [Socket.io] 库和 [Node.js]。

Throughout the development of [AngularJS], we've been using [JSTD] for
testing. I really think that JSTD is a great idea. Unfortunately, we
had many problems with JSTD, so we decided to write our own test
runner based on the same idea. We wanted a simple tool just for
executing JavaScript tests that is both stable and fast. That's why we
use the awesome [Socket.io] library and [Node.js].


## 我的老板想要一个许可证。那么它在哪里呢？
[MIT License](./LICENSE)


[AngularJS]: https://angularjs.org/
[JSTD]: https://code.google.com/p/js-test-driver/
[Socket.io]: http://socket.io/
[Node.js]: http://nodejs.org/
[Jasmine]: https://github.com/karma-runner/karma-jasmine
[Mocha]: https://github.com/karma-runner/karma-mocha
[QUnit]: https://github.com/karma-runner/karma-qunit
[here]: https://www.youtube.com/watch?v=MVw8N3hTfCI
[Mailing List]: https://groups.google.com/forum/#!forum/karma-users
[Issue Tracker]: https://github.com/karma-runner/karma/issues
[@JsKarma]: https://twitter.com/JsKarma
[RequireJS]: http://requirejs.org/
[Istanbul]: https://github.com/gotwarlost/istanbul

[browsers]: https://karma-runner.github.io/latest/config/browsers.html
[documentation]: https://karma-runner.github.io
