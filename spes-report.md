**Test-Report**

**Spec Files:**      6 passed, 3 failed, 9 total (100% completed) in 00:08:08

**Spec 1**

\tests\specs\app.biometric.login.spec.ts

? should be able to login with a matching touch/faceID/fingerprint  
✖ "before each" hook for WebdriverIO and Appium, when interacting with a biometric button,

1 failing (49.9s)
WebdriverIO and Appium, when interacting with a biometric button, "before each" hook for WebdriverIO and Appium, when interacting with a biometric button,
element ("android=new UiSelector().textContains("NEXT")") still not displayed after 45000ms  
Error: element ("android=new UiSelector().textContains("NEXT")") still not displayed after 45000ms

***

**Spec 2**

\tests\specs\app.deep.link.navigation.spec.ts

✓ should be able to open the webview  
✓ should be able to open the login form screen  
✓ should be able to open the forms screen  
✓ should be able to open the swipe screen  
✓ should be able to open the drag and drop screen  
✓ should be able to open the home screen  

6 passing (28.9s)

***

**Spec 3**

\tests\specs\app.drag.and.drop.spec.ts

✓ should be able to solve the puzzle by dragging the pieces into the puzzle

1 passing (18.9s)

***

**Spec 4**

\tests\specs\app.forms.spec.ts

✓ should be able type in the input and validate the text  
✓ should be able turn on and off the switch  
✖ should be able select a value from the select element  
✓ should be able to open the alert and close it with all 3 buttons  
✓ should be able to determine that the inactive button is inactive  

4 passing (1m 2.1s)

1 failing
WebdriverIO and Appium, when interacting with form elements, should be able select a value from the select element
Can't call click on element with selector "~Dropdown" because element wasn't found  
Error: Can't call click on element with selector "~Dropdown" because element wasn't found

Issue: https://github.com/tanyajoe/appium-boilerplate/issues/1

***

**Spec 5**

\tests\specs\app.login.spec.ts

✓ should be able login successfully  
✓ should be able sign up successfully

2 passing (25.5s)

***

**Spec 6**

\tests\specs\app.swipe.spec.ts

✓ should be able to swipe horizontal by swiping the carousel from left to right  
✓ should be able to swipe vertical by finding the surprise

2 passing (40.6s)

***

**Spec 7**

\tests\specs\app.tab.bar.navigation.spec.ts

✓ should be able to open the webview  
✓ should be able to open the login form screen  
✓ should be able to open the forms screen  
✓ should be able to open the swipe screen  
✓ should be able to open the drag and drop screen  
✓ should be able to open the home screen  

6 passing (26.6s)

***

**Spec 8**

\tests\specs\app.webview.spec.ts

✖ should be able to switch between webview, native and webview

1 failing (1m 1.6s)
WebdriverIO and Appium, when interacting with a WebView, should be able to switch between webview, native and webview
element (".DocSearch-Input") still not displayed after 45000ms  
Error: element (".DocSearch-Input") still not displayed after 45000ms

***

**Spec 9**

\tests\specs\app.webview.xpath.spec.ts

✓ should be able to verify that the WebView is shown by xpath  
✓ should be able to verify that the WebView is shown by switching to the WebView

2 passing (15.8s)
