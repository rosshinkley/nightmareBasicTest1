# nightmareBasicTest1
1) Run nightProxy.js to test proxy is working. Taken from nightmarejs examples<br />
2) run rxNightmare.js for main script run<br />

## Issues
1) clearCache() causes electron to run , but it leaves a blank white screen <br />
2) The site seems to be providing unpredictable responses. Currently, it fails at `.click('.ui-searchbar-submit')`.<br />
 it will take me to the login screen for no apparent reason. See image below. Kindly note my email is recorded in browser. Due to caching? <br />
 ![Screenshot](loginpage.jpg)

## Attempts to fix
1) I have tried using Proxy IP Rotation. The proxy works, but seems to no effect <br />
2) Using clearCache() but with issue above(1) <br />
3) Using custom useragent.  <br />
</br />
4) Is it possible to simulate mouse movements. Lack of mosuemovements could be a way siteadmin is filtering out bots from Humans??