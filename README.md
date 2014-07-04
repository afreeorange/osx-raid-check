# RAID Health Check for OS X

Since this should be a thing. Can tell you about a degraded/failed set via email and the Notification Center. In an ideal universe, you'd be notified the _moment_ something awful happens, but this is better than nothing.

## Installation

Install [`terminal-notifier`](https://github.com/alloy/terminal-notifier)

	brew install terminal-notifier
	brew linkapps

Change the `$EMAIL` variable. Then make it a cron job. Fin.