# Appium Workshop Content Proposal


## Pre-requisites
1. Installing node (MacOS, Win, Linux) 

> This can be a pre-requirement.

2. Installing Appium `npm i -g appium`
3. Choose an Appium client
	* [python](https://github.com/appium/python-client)
	* [node](https://github.com/admc/wd)
	* [ruby](https://github.com/appium/ruby_lib)
	* [java](https://github.com/appium/java-client)
	* [php](https://github.com/appium/php-client)

3. Prepare the environment to use the appium client selected

## Newbie

4. Explain what are capabilities
5. Run the appium server
6. Write a simple browser test to check a document title on a Android emulator
7. Change the capabilities to run the same tests on an iOS Simulator
> The idea here is to show devs how the same tests can be used for testing Android and iOS
8. Write a test to find elements in Android
	* Find elements by ID
	* Find elemenys by class

9. Write a test to interact with elements
	* Clear a textbox
	* click on a button

10. Change the capabilities on the test created on item *9.* to use iOS
11. Explain the capabilities needed to run an native app
12. Use the same test writed on item 9. a test to interact with elements on a native Android app 
13. Change the capabilities to run test created on item *12.* on an iOS Simulator
> The idea is to show devs that appium can use same methods to inetract with elements on their webapps/native apps. 
14. Introduce native testing strategies for finding elements
	* Find elements by Localtor
	* Find elements by XPATH
15. Explain pros & cons on finding elements strategies
> Why using Xpath is not a right solution? Why using ids make testing easier?
16. Write a test to work with an hybrid app on Android app. 
	* Change contexts
	* Find element by Id

## Intermediate - TBD
17. Touch actions
18. Hardware interaction

## Advanced - TBD
19. Parallel testing
20. Performance testing
	
