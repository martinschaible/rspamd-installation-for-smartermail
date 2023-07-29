## Rspamd Installation for use with Smartermail

:information_source: This is a guide to install and configure Rspamd for use with SmarterMail.

Since build 8510 (April 20, 2023) [SmarterMail](https://www.smartertools.com/smartermail/business-email-server) supports the long-awaited spam filtering system called  [Rspamd](https://rspamd.com/).

Rspamd runs on a separate linux server.

The installation isn't really hard, but the configuration could be tricky and needs time to understand concept :bulb: 

:arrow_right: Let's head over the [Wiki](../../wiki). I think one hour time is enough to accomplish this work.

### Additional Links:

* [Rspamd Documentation](https://rspamd.com/doc/index.html)
* [Rspamd Github](https://github.com/rspamd/rspamd)
* [Deploying Rspamd For Use With SmarterMail](https://portal.smartertools.com/kb/a3595/deploying-rspamd-for-use-with-smartermail.aspx?KBSearchID=904007)

## What's next?

Rspamd needs tweaking to combat against spam. New specific modules have to be developed, which mainly combat country-specific spam and malware.
For this, i will create a separate a new repository.

