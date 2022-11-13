# jenkins

Cron: This is a default scheduer in linux
triggers { cron('H */4 * * 1-5') }

This job runs all the weekdays apart from Sunday & saturday once in every 4 hours
We can use cronmaker or corntab to schedule other than this

pollSCM: This will check for the commits on github and if there are any commits it will run the job

All the slaves need tohave Java installed as Jenkins is Java based