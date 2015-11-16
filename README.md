##Gradle plugin to execute JMeter tests. 

For usage see: http://jmeter.foragerr.net/  
or [wiki](https://github.com/jmeter-gradle-plugin/jmeter-gradle-plugin/wiki/Getting-Started)

##News
**11/15/2015**
* Stable version 1.0.2 released.
* Added out of box support for jp@gc plugins for both test execution and gui mode

**11/11/2015**
* version 1.0.1 released.
* Added support for passing -D and -XX type arguments to the JMeter jvm. [See here](https://github.com/jmeter-gradle-plugin/jmeter-gradle-plugin/issues/37).

**11/6/2015**
* Stable version 1.0 released. 
* This plugin is now also available from the [Gradle plugins page](https://plugins.gradle.org/)
* With gradle (ver>2.1) the plugin can be used with this shorthand:  

		plugins {
		  id "net.foragerr.jmeter" version "1.0-2.13"
		}

##Attribution
This project started as a hard fork of [kulya/jmeter-gradle-plugin](https://github.com/kulya/jmeter-gradle-plugin). Besides defect fixes and feature enhancements, most of the original codebase has been re-written since. 

If you are a user of the older plugin see [here]() for easy migration to this version of the plugin. If you're a developer familiar with the older plugin, see [here]() for notes about major changes.
