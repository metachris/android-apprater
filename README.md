android-apprater is a one-file library to prompt engaged users to
rate your app on the Android market. Inspired by:

* http://amro.co/how-to-get-4-to-5-stars-on-the-app-store
* http://arashpayan.com/blog/index.php/2009/09/07/presenting-appirater/

AppRater requires a certain number of launches of the app and days 
since the installation before the rating dialog appears.

Adjust APP_TITLE and APP_PNAME to your needs. You should also tweak
DAYS_UNTIL_PROMPT and LAUNCHES_UNTIL_PROMPT.
 
To test it and to tweak the dialog appearence, you can call
`AppRater.showRateDialog(this, null)` from your Activity.
 
Normal use is to invoke `AppRater.app_launched(this)` each time your 
activity is invoked (eg. from within the onCreate method).
 
License: MIT/BSD
