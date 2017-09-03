# PGR301-exercise-1

Sett opp Jenkins med Docker feks. med oppskrift herfra: https://github.com/jenkinsci/docker

Lag et git-repo på github e.l. med en fil som heter "Jenkinsfile". En minimal Jenkinsfile ligger på git-repoet. 

I jenkins, trykk "New Item" -> "Pipeline" -> "OK"

I jobbkonfig under "Pipeline", velg "Pipeline script from SCM", SCM: Git, Repository URL: <link til github>, Credentials: None. Script Path: Jenkinsfile (med mindre du har kalt din Jenkinsfile noe annet). Velg "Save."



