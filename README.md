# jenkins

Cron: This is a default scheduer in linux
triggers { cron('H */4 * * 1-5') }

This job runs all the weekdays apart from Sunday & saturday once in every 4 hours
We can use cronmaker or corntab to schedule other than this