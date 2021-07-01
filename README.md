# Login fail notifier for ProcessWire

This module for ProcessWire sends a notification email for each failed login attempt.

!["Screenshot showing the module settings"](https://tech-c.net/site/assets/files/1197/screenshot.jpg)

## Settings
The settings for this module are located int the menu Modules=>Configure=>LoginFailNotifier.

* Notification email
Specifies the email address to which the notification emails should be sent.

* Email subject
Specifies the subject line for the notification email.

* Post variables
Specifies the $_POST variables to be included in the notification email. Each variable must be separated by a comma. For example: login_name,login_pass

* Server variables
Specifies the $_SERVER variables to be included in the notification email. Each variable must be separated by a comma. For example: REMOTE_ADDR,HTTP_USER_AGENT
