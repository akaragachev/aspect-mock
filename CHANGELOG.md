# Changelog

#### 5.0.0

* Changed php version to ^8.0
* Switched goaop/framework to lanfix/goaop-framework

#### 3.0.0

* Upgraded to Go AOP 2.2 
* PHPUnit > 6.x support

#### 2.1.0

* Add missing type hints and parameter types to FuncProxy. See #135 by @SenseException
* Added support for optional and referenced parameters in built-in functions. See #133 by @bhoehl
* Fixed `return void` issue #123 by @zuozp8. See #130

#### 2.0.0

* **Updated to Go AOP Framework 2.0**
* PHP7 (with typehints) supported
* Minimal PHP version is PHP 5.6

#### 1.0.0

* **Updated to Go AOP Framework 1.0**
* Added verifying inherited method calls by @torreytsui. See #90
* Replaces `return` with `yield` for non-root namespaces. By @faridanthony See #93
* Fix bug that class does not bind in static double by @torreytsui. See #89

#### 0.5.5

* compatible with Symfony3 and PHP7

#### 0.5.4

* Improved namespace handling
* Added ability to display actually passed parameter in the error message
* Fixed counting of dynamic class methods (#24)
* Fixes for functions that have a brace as default on parametersi
* Replace return with yield when docComments returns Generator


#### 0.5.3

* Updated to lanfix/goaop-framework 0.6.x and codeception 2.1


#### 0.5.1

* Fixed strict errors for func verifier


#### 0.5.0

* `test::ns` method removed
* Mocking functions implemented with `test::func` method
* Fixed mocking functions with arguments passed by reference (#34)
* Fixed passing arguments by reference in InstanceProxy
* Debug mode can be disabled in options with `debug => false`
* Updated to Lanfix\Aop 0.5.0


#### 0.5.0-beta 05/14/2014

* Moved to Lanfix\Aop 0.5.x-dev


#### 0.4.2 05/09/2014

* Depdendency on AspectMock ~0.4.0


#### 0.4.1

* RoboFile
* Verify invocation arguments with closures
* Verify invocation arguments with closures
* Vetter support for traits
