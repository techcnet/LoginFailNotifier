# Login fail notifier for ProcessWire

![GitHub](https://img.shields.io/github/license/techcnet/LoginFailNotifier)
![GitHub last commit](https://img.shields.io/github/last-commit/techcnet/LoginFailNotifier)
[![](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/techcnet)

This module for ProcessWire sends a notification email for each failed login attempt. Similar modules exists already in the module directory of ProcessWire. However, this module is designed to notify, even if specified user doesn't exist.

## Settings
The settings for this module are located in the menu Modules=>Configure=>LoginFailNotifier.

* Notification email
Specifies the email address to which the notification emails should be sent.

* Email subject
Specifies the subject line for the notification email.

* Post variables
Specifies the $_POST variables to be included in the notification email. Each variable must be separated by a comma. For example: login_name,login_pass

* Server variables
Specifies the $_SERVER variables to be included in the notification email. Each variable must be separated by a comma. For example: REMOTE_ADDR,HTTP_USER_AGENT

!["Screenshot showing the module settings"](https://tech-c.net/site/assets/files/1197/screenshot.jpg)
