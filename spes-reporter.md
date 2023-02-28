"spec" Reporter:
------------------------------------------------------------------
[emulator-5554 Android 7.0 #0-0] Running: emulator-5554 on Android 7.0 executing C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\apps\Android-NativeDemoApp-0.4.0.apk
[emulator-5554 Android 7.0 #0-0] Session ID: 89059fa3-9d3a-4978-b579-d1d056a08226
[emulator-5554 Android 7.0 #0-0]
[emulator-5554 Android 7.0 #0-0] » \tests\specs\app.biometric.login.spec.ts
[emulator-5554 Android 7.0 #0-0] WebdriverIO and Appium, when interacting with a biometric button,
[emulator-5554 Android 7.0 #0-0]    ? should be able to login with a matching touch/faceID/fingerprint
[emulator-5554 Android 7.0 #0-0]    ✖ "before each" hook for WebdriverIO and Appium, when interacting with a biometric button,
[emulator-5554 Android 7.0 #0-0]
[emulator-5554 Android 7.0 #0-0] 1 failing (1m 0.9s)
[emulator-5554 Android 7.0 #0-0]
[emulator-5554 Android 7.0 #0-0] 1) WebdriverIO and Appium, when interacting with a biometric button, "before each" hook for WebdriverIO and Appium, when interacting with a biometric button,
[emulator-5554 Android 7.0 #0-0] element ("android=new UiSelector().textContains("NEXT")") still not displayed after 45000ms
[emulator-5554 Android 7.0 #0-0] Error: element ("android=new UiSelector().textContains("NEXT")") still not displayed after 45000ms        
[emulator-5554 Android 7.0 #0-0]     at C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\webdriverio\build\commands\browser\waitUntil.js:66:23
[emulator-5554 Android 7.0 #0-0]     at async Element.wrapCommandFn (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\@wdio\utils\build\shim.js:137:29)
[emulator-5554 Android 7.0 #0-0]     at async Element.elementErrorHandlerCallbackFn (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\webdriverio\build\middlewares.js:24:32)
[emulator-5554 Android 7.0 #0-0]     at async Element.wrapCommandFn (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\@wdio\utils\build\shim.js:137:29)
[emulator-5554 Android 7.0 #0-0]     at async Element.wrapCommandFn (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\@wdio\utils\build\shim.js:137:29)
[emulator-5554 Android 7.0 #0-0]     at async Element.elementErrorHandlerCallbackFn (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\webdriverio\build\middlewares.js:24:32)
[emulator-5554 Android 7.0 #0-0]     at async Element.wrapCommandFn (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\@wdio\utils\build\shim.js:137:29)
[emulator-5554 Android 7.0 #0-0]     at async AndroidSettings.waitAndTap (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\tests\screenobjects\AndroidSettings.ts:113:9)
[emulator-5554 Android 7.0 #0-0]     at async AndroidSettings.fingerPrintWizardSevenOrLower (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\tests\screenobjects\AndroidSettings.ts:19:9)
[emulator-5554 Android 7.0 #0-0]     at async AndroidSettings.enableBiometricLogin (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\tests\screenobjects\AndroidSettings.ts:130:13)
------------------------------------------------------------------
[emulator-5554 Android 7.0 #0-1] Running: emulator-5554 on Android 7.0 executing C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\apps\Android-NativeDemoApp-0.4.0.apk
[emulator-5554 Android 7.0 #0-1] Session ID: 2abaf1c2-696e-4b3b-acac-e6f5a72b7eea
[emulator-5554 Android 7.0 #0-1]
[emulator-5554 Android 7.0 #0-1] » \tests\specs\app.deep.link.navigation.spec.ts
[emulator-5554 Android 7.0 #0-1] WebdriverIO and Appium, when navigating by deep link
[emulator-5554 Android 7.0 #0-1]    ✓ should be able to open the webview
[emulator-5554 Android 7.0 #0-1]    ✓ should be able to open the login form screen
[emulator-5554 Android 7.0 #0-1]    ✓ should be able to open the forms screen
[emulator-5554 Android 7.0 #0-1]    ✓ should be able to open the swipe screen
[emulator-5554 Android 7.0 #0-1]    ✓ should be able to open the drag and drop screen
[emulator-5554 Android 7.0 #0-1]    ✓ should be able to open the home screen
[emulator-5554 Android 7.0 #0-1]
[emulator-5554 Android 7.0 #0-1] 6 passing (50.1s)
------------------------------------------------------------------
[emulator-5554 Android 7.0 #0-2] Running: emulator-5554 on Android 7.0 executing C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\apps\Android-NativeDemoApp-0.4.0.apk
[emulator-5554 Android 7.0 #0-2] Session ID: dae062c1-e616-4b6e-9f7f-02b0f4bb3596
[emulator-5554 Android 7.0 #0-2]
[emulator-5554 Android 7.0 #0-2] » \tests\specs\app.drag.and.drop.spec.ts
[emulator-5554 Android 7.0 #0-2] WebdriverIO and Appium, when using drag and drop
[emulator-5554 Android 7.0 #0-2]    ✖ should be able to solve the puzzle by dragging the pieces into the puzzle
[emulator-5554 Android 7.0 #0-2]
[emulator-5554 Android 7.0 #0-2] 1 failing (3m 5.3s)
[emulator-5554 Android 7.0 #0-2]
[emulator-5554 Android 7.0 #0-2] 1) WebdriverIO and Appium, when using drag and drop should be able to solve the puzzle by dragging the pieces into the puzzle
[emulator-5554 Android 7.0 #0-2] element ("~button-Retry") still not displayed after 45000ms
[emulator-5554 Android 7.0 #0-2] Error: element ("~button-Retry") still not displayed after 45000ms
[emulator-5554 Android 7.0 #0-2]     at C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\webdriverio\build\commands\browser\waitUntil.js:66:23
[emulator-5554 Android 7.0 #0-2]     at async Element.wrapCommandFn (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\@wdio\utils\build\shim.js:137:29)
[emulator-5554 Android 7.0 #0-2]     at async Element.elementErrorHandlerCallbackFn (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\webdriverio\build\middlewares.js:24:32)
[emulator-5554 Android 7.0 #0-2]     at async Element.wrapCommandFn (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\@wdio\utils\build\shim.js:137:29)
[emulator-5554 Android 7.0 #0-2]     at async Element.wrapCommandFn (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\@wdio\utils\build\shim.js:137:29)
[emulator-5554 Android 7.0 #0-2]     at async Element.elementErrorHandlerCallbackFn (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\webdriverio\build\middlewares.js:24:32)
[emulator-5554 Android 7.0 #0-2]     at async Element.wrapCommandFn (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\@wdio\utils\build\shim.js:137:29)
[emulator-5554 Android 7.0 #0-2]     at async Context.<anonymous> (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. 
MOBILE AUTOMATION\boiler\appium-boilerplate\tests\specs\app.drag.and.drop.spec.ts:25:9)
------------------------------------------------------------------
[emulator-5554 Android 7.0 #0-3] Running: emulator-5554 on Android 7.0 executing C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\apps\Android-NativeDemoApp-0.4.0.apk
[emulator-5554 Android 7.0 #0-3] Session ID: 8f52d69f-7f76-45d4-908d-4ecc1ea675d8
[emulator-5554 Android 7.0 #0-3]
[emulator-5554 Android 7.0 #0-3] » \tests\specs\app.forms.spec.ts
[emulator-5554 Android 7.0 #0-3] WebdriverIO and Appium, when interacting with form elements,
[emulator-5554 Android 7.0 #0-3]    ✓ should be able type in the input and validate the text
[emulator-5554 Android 7.0 #0-3]    ✓ should be able turn on and off the switch
[emulator-5554 Android 7.0 #0-3]    ✖ should be able select a value from the select element
[emulator-5554 Android 7.0 #0-3]    ✓ should be able to open the alert and close it with all 3 buttons
[emulator-5554 Android 7.0 #0-3]    ✓ should be able to determine that the inactive button is inactive
[emulator-5554 Android 7.0 #0-3]
[emulator-5554 Android 7.0 #0-3] 4 passing (2m 32.5s)
[emulator-5554 Android 7.0 #0-3] 1 failing
[emulator-5554 Android 7.0 #0-3]
[emulator-5554 Android 7.0 #0-3] 1) WebdriverIO and Appium, when interacting with form elements, should be able select a value from the select element
[emulator-5554 Android 7.0 #0-3] Can't call click on element with selector "~Dropdown" because element wasn't found
[emulator-5554 Android 7.0 #0-3] Error: Can't call click on element with selector "~Dropdown" because element wasn't found
[emulator-5554 Android 7.0 #0-3]     at implicitWait (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\webdriverio\build\utils\implicitWait.js:34:19)
[emulator-5554 Android 7.0 #0-3]     at async Element.elementErrorHandlerCallbackFn (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\webdriverio\build\middlewares.js:20:29)
[emulator-5554 Android 7.0 #0-3]     at async Element.wrapCommandFn (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\@wdio\utils\build\shim.js:137:29)
[emulator-5554 Android 7.0 #0-3]     at async FormsScreen.tapOnDropDown (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\tests\screenobjects\FormsScreen.ts:25:9)
[emulator-5554 Android 7.0 #0-3]     at async Context.<anonymous> (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. 
MOBILE AUTOMATION\boiler\appium-boilerplate\tests\specs\app.forms.spec.ts:56:9)
------------------------------------------------------------------
[emulator-5554 Android 7.0 #0-4] Running: emulator-5554 on Android 7.0 executing C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\apps\Android-NativeDemoApp-0.4.0.apk
[emulator-5554 Android 7.0 #0-4] Session ID: ac5a41f8-5c2b-4590-969c-ec56e9453226
[emulator-5554 Android 7.0 #0-4]
[emulator-5554 Android 7.0 #0-4] » \tests\specs\app.login.spec.ts
[emulator-5554 Android 7.0 #0-4] WebdriverIO and Appium, when interacting with a login form,
[emulator-5554 Android 7.0 #0-4]    ✓ should be able login successfully
[emulator-5554 Android 7.0 #0-4]    ✓ should be able sign up successfully
[emulator-5554 Android 7.0 #0-4]
[emulator-5554 Android 7.0 #0-4] 2 passing (1m 50.7s)
------------------------------------------------------------------
[emulator-5554 Android 7.0 #0-5] Running: emulator-5554 on Android 7.0 executing C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\apps\Android-NativeDemoApp-0.4.0.apk
[emulator-5554 Android 7.0 #0-5] Session ID: e5516231-43e7-468e-92f5-84efc54f0369
[emulator-5554 Android 7.0 #0-5]
[emulator-5554 Android 7.0 #0-5] » \tests\specs\app.swipe.spec.ts
[emulator-5554 Android 7.0 #0-5] WebdriverIO and Appium, when using swiping
[emulator-5554 Android 7.0 #0-5]    ✖ should be able to swipe horizontal by swiping the carousel from left to right
[emulator-5554 Android 7.0 #0-5]    ✖ should be able to swipe vertical by finding the surprise
[emulator-5554 Android 7.0 #0-5]
[emulator-5554 Android 7.0 #0-5] 2 failing (6m 40.1s)
[emulator-5554 Android 7.0 #0-5]
[emulator-5554 Android 7.0 #0-5] 1) WebdriverIO and Appium, when using swiping should be able to swipe horizontal by swiping the carousel from left to right
[emulator-5554 Android 7.0 #0-5] Timeout of 180000ms exceeded. The execution in the test "WebdriverIO and Appium, when using swiping should be able to swipe horizontal by swiping the carousel from left to right" took too long. Try to reduce the run time or increase your timeout for test specs (https://webdriver.io/docs/timeouts). (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\tests\specs\app.swipe.spec.ts)
[emulator-5554 Android 7.0 #0-5] Error: Timeout of 180000ms exceeded. The execution in the test "WebdriverIO and Appium, when using swiping should be able to swipe horizontal by swiping the carousel from left to right" took too long. Try to reduce the run time or increase your 
timeout for test specs (https://webdriver.io/docs/timeouts). (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\tests\specs\app.swipe.spec.ts)
[emulator-5554 Android 7.0 #0-5]     at createTimeoutError (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE 
AUTOMATION\boiler\appium-boilerplate\node_modules\mocha\lib\errors.js:498:15)
[emulator-5554 Android 7.0 #0-5]     at Test.Runnable._timeoutError (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\mocha\lib\runnable.js:431:10)
[emulator-5554 Android 7.0 #0-5]     at Timeout.<anonymous> (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\mocha\lib\runnable.js:246:24)
[emulator-5554 Android 7.0 #0-5]     at listOnTimeout (node:internal/timers:564:17)
[emulator-5554 Android 7.0 #0-5]     at processTimers (node:internal/timers:507:7)
[emulator-5554 Android 7.0 #0-5]
[emulator-5554 Android 7.0 #0-5] 2) WebdriverIO and Appium, when using swiping should be able to swipe vertical by finding the surprise    
[emulator-5554 Android 7.0 #0-5] Timeout of 180000ms exceeded. The execution in the test "WebdriverIO and Appium, when using swiping should be able to swipe vertical by finding the surprise" took too long. Try to reduce the run time or increase your timeout for test specs (https://webdriver.io/docs/timeouts). (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\tests\specs\app.swipe.spec.ts)
[emulator-5554 Android 7.0 #0-5] Error: Timeout of 180000ms exceeded. The execution in the test "WebdriverIO and Appium, when using swiping should be able to swipe vertical by finding the surprise" took too long. Try to reduce the run time or increase your timeout for test specs (https://webdriver.io/docs/timeouts). (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\tests\specs\app.swipe.spec.ts)
[emulator-5554 Android 7.0 #0-5]     at createTimeoutError (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE 
AUTOMATION\boiler\appium-boilerplate\node_modules\mocha\lib\errors.js:498:15)
[emulator-5554 Android 7.0 #0-5]     at Test.Runnable._timeoutError (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\mocha\lib\runnable.js:431:10)
[emulator-5554 Android 7.0 #0-5]     at Timeout.<anonymous> (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\mocha\lib\runnable.js:246:24)
[emulator-5554 Android 7.0 #0-5]     at listOnTimeout (node:internal/timers:564:17)
[emulator-5554 Android 7.0 #0-5]     at processTimers (node:internal/timers:507:7)
------------------------------------------------------------------
[emulator-5554 Android 7.0 #0-6] Running: emulator-5554 on Android 7.0 executing C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\apps\Android-NativeDemoApp-0.4.0.apk
[emulator-5554 Android 7.0 #0-6] Session ID: 9a76425e-f5ee-47e1-accf-d70a3cf471a1
[emulator-5554 Android 7.0 #0-6]
[emulator-5554 Android 7.0 #0-6] » \tests\specs\app.tab.bar.navigation.spec.ts
[emulator-5554 Android 7.0 #0-6] WebdriverIO and Appium, when using navigation through the tab bar
[emulator-5554 Android 7.0 #0-6]    ✓ should be able to open the webview
[emulator-5554 Android 7.0 #0-6]    ✓ should be able to open the login form screen
[emulator-5554 Android 7.0 #0-6]    ✓ should be able to open the forms screen
[emulator-5554 Android 7.0 #0-6]    ✓ should be able to open the swipe screen
[emulator-5554 Android 7.0 #0-6]    ✓ should be able to open the drag and drop screen
[emulator-5554 Android 7.0 #0-6]    ✓ should be able to open the home screen
[emulator-5554 Android 7.0 #0-6]
[emulator-5554 Android 7.0 #0-6] 6 passing (52.8s)
------------------------------------------------------------------
[emulator-5554 Android 7.0 #0-7] Running: emulator-5554 on Android 7.0 executing C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\apps\Android-NativeDemoApp-0.4.0.apk
[emulator-5554 Android 7.0 #0-7] Session ID: 88acbb6f-08b5-47d1-83a3-e537f571ca08
[emulator-5554 Android 7.0 #0-7]
[emulator-5554 Android 7.0 #0-7] » \tests\specs\app.webview.spec.ts
[emulator-5554 Android 7.0 #0-7] WebdriverIO and Appium, when interacting with a WebView,
[emulator-5554 Android 7.0 #0-7]    ✖ should be able to switch between webview, native and webview
[emulator-5554 Android 7.0 #0-7]
[emulator-5554 Android 7.0 #0-7] 1 failing (1m 5.5s)
[emulator-5554 Android 7.0 #0-7]
[emulator-5554 Android 7.0 #0-7] 1) WebdriverIO and Appium, when interacting with a WebView, should be able to switch between webview, native and webview
[emulator-5554 Android 7.0 #0-7] element (".DocSearch-Input") still not displayed after 45000ms
[emulator-5554 Android 7.0 #0-7] Error: element (".DocSearch-Input") still not displayed after 45000ms
[emulator-5554 Android 7.0 #0-7]     at C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\webdriverio\build\commands\browser\waitUntil.js:66:23
[emulator-5554 Android 7.0 #0-7]     at async Element.wrapCommandFn (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\@wdio\utils\build\shim.js:137:29)
[emulator-5554 Android 7.0 #0-7]     at async Element.elementErrorHandlerCallbackFn (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\webdriverio\build\middlewares.js:24:32)
[emulator-5554 Android 7.0 #0-7]     at async Element.wrapCommandFn (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\@wdio\utils\build\shim.js:137:29)
[emulator-5554 Android 7.0 #0-7]     at async Element.wrapCommandFn (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\@wdio\utils\build\shim.js:137:29)
[emulator-5554 Android 7.0 #0-7]     at async Element.elementErrorHandlerCallbackFn (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\webdriverio\build\middlewares.js:24:32)
[emulator-5554 Android 7.0 #0-7]     at async Element.wrapCommandFn (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\node_modules\@wdio\utils\build\shim.js:137:29)
[emulator-5554 Android 7.0 #0-7]     at async Context.<anonymous> (C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. 
MOBILE AUTOMATION\boiler\appium-boilerplate\tests\specs\app.webview.spec.ts:63:9)
------------------------------------------------------------------
[emulator-5554 Android 7.0 #0-8] Running: emulator-5554 on Android 7.0 executing C:\Users\Татьяна\Desktop\QA auto\QA automation\QA automation\МОДУЛЬ 12. MOBILE AUTOMATION\boiler\appium-boilerplate\apps\Android-NativeDemoApp-0.4.0.apk
[emulator-5554 Android 7.0 #0-8] Session ID: fbf90d4b-01c9-4228-b406-816343133017
[emulator-5554 Android 7.0 #0-8]
[emulator-5554 Android 7.0 #0-8] » \tests\specs\app.webview.xpath.spec.ts
[emulator-5554 Android 7.0 #0-8] WebdriverIO and Appium, when interacting with a webview through XPATH
[emulator-5554 Android 7.0 #0-8]    ✓ should be able to verify that the WebView is shown by xpath
[emulator-5554 Android 7.0 #0-8]    ✓ should be able to verify that the WebView is shown by switching to the WebView
[emulator-5554 Android 7.0 #0-8]
[emulator-5554 Android 7.0 #0-8] 2 passing (34.8s)


Spec Files:      4 passed, 5 failed, 9 total (100% completed) in 00:21:29

2023-02-28T20:20:19.993Z INFO @wdio/local-runner: Shutting down spawned worker
2023-02-28T20:20:20.253Z INFO @wdio/local-runner: Waiting for 0 to shut down gracefully
2023-02-28T20:20:20.257Z INFO @wdio/local-runner: shutting down