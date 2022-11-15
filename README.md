# jenkins

Cron: This is a default scheduer in linux
triggers { cron('H */4 * * 1-5') }

This job runs all the weekdays apart from Sunday & saturday once in every 4 hours
We can use cronmaker or corntab to schedule other than this

pollSCM: This will check for the commits on github and if there are any commits it will run the job

### USED TO GET THE PASSWORD

sudo cat /var/lib/jenkins/secrets/initialAdminPassword

All the slaves need tohave Java installed as Jenkins is Java based

### SonarQube : A tools from sonarqube to help un scanning our code and publishing the result to SonarQube

...
Sonar Scanner:
1) A tools from sonarqube to help in scanning our code and iublishing the result to sonarQube. 
2)Install sonarscanner on Jenkins or jenkis agent where your job will run. Then only you can take advantage of SonarCode Scanner.

Quality gate:

Quality Profile:

...