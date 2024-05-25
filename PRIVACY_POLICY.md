# eFeza: Privacy policy

Welcome to the eFeza app for Android!

This is an open source Android app developed by HOGI. The source code is available on GitHub under the HOGI license; the app is also available on Google Play.

As an avid Android user myself, I take privacy very seriously.
I know how irritating it is when apps collect your data without your knowledge.

I hereby state, to the best of my knowledge and belief, that I have not programmed this app to collect any personally identifiable information. All data (app preferences (like theme, etc.) and alarms) created by the you (the user) is stored on your device only, and can be simply erased by clearing the app's data or uninstalling it.

## Explanation of permissions requested in the app

The list of permissions required by the app can be found in the `AndroidManifest.xml` file

| Permission | Why it is required |
| :---: | --- |
| `android.permission.FOREGROUND_SERVICE` | Enables the app to create foreground services that will popup notifications. Permission automatically granted by the system; can't be revoked by user. |
| `android.permission.READ_EXTERNAL_STORAGE` and `android.permission.WRITE_EXTERNAL_STORAGE` | The only sensitive permissions that the app requests, and can be revoked by the system or the user at any time. This is required only for screenshot taken before sharing it on gmail. |
| `android.permission.USE_BIOMETRIC` | This permission is used by our application to access biometric features of the device. App requests this permission to enhance security by providing a convenient and secure way for users to authenticate their identity. |

---

If you find any security vulnerability that has been inadvertently caused by me, or have any question regarding how the app protectes your privacy, please send me an email or post a discussion on GitHub, and I will surely try to fix it/help you.

Yours sincerely,  
HOGI  
Bujumbura, Burundi.
<hello@hogi.bi>
