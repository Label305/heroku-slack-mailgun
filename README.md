# Mailgun webhook to Slack webhook proxy on Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Label305/heroku-slack-mailgun)

Simple proxy to route a Mailgun webhook call to a Slack webhook. Deploy free to heroku with one click.

Your webhook URL will be: `https://{yourapp}.herokuapp.com/api/mailgun`.

![screenshot](https://user-images.githubusercontent.com/44893/36527406-f4f57862-17b1-11e8-85ce-5ba3217b4cb6.png)

**This proxy has nothing to do with the Mailgun addon for other Heroku apps.** It is purley a simple proxy so you can be notified of failed emails for **any** Mailgun account (also regular Mailgun accounts, which are not Heroku addons).
