Introduction
============

This is a presentation on Load/Performance testing using JMeter, plus a sample project that is ready to be built using Maven and the Performance plugin.

1\. The examples\\sample folder
----------------------

This folder contains the sample Maven project that contains the sample JMeter test plan used in the presentation. To run the test, simply install maven and run this in the command line: 

	'mvn clean verify'

2\. The examples\\advanced-examples folder
----------------------

This folder contains more advanced examples for handling the different use cases:

*	Using a random-variable in your test case.
*	Using a transaction controller to group your test cases.
*	Using the result of a request in the subsequent request.
