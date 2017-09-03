# PGR301-exercise-1

Sett opp Jenkins med Docker feks. med oppskrift herfra: https://github.com/jenkinsci/docker

Lag et git-repo på github e.l. med en fil som heter "Jenkinsfile". En minimal Jenkinsfile ligger på git-repoet. 

I jenkins, trykk "New Item" -> "Pipeline" -> "OK"

I jobbkonfig under "Pipeline", velg "Pipeline script from SCM", SCM: Git, Repository URL: <link til github>, Credentials: None. Script Path: Jenkinsfile (med mindre du har kalt din Jenkinsfile noe annet). Velg "Save."

Kjør Jenkinsjobben og verifiser at den fungerer ved å trykke på jobben og velge "Console Output". Du ønsker output som ser ca slik ut: 

[oving1Pipeline] Running shell script
\+ echo Hello World
Hello World



