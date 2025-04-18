# DevOps 07 CI1

## Lernjournal


ich habe mal als erstes das Jenkins Image gepulled: (![JenkinsImage](images/JenkinsImage.png))

desweiteren habe ich das plugin installiert: (![JenkinsPlugin](images/JenkinsPlugin.png))

Ihc habe das Projekt gemäss Anelitung erstellt und dann das Github-Token an Jenkins übergeben:(![githubTokenToJenkins](images/githubTokenToJenkins.png)) (![RepoAdded](images/RepoAdded.png)) 

ich hatte noch ein Problem mit Execution Rechten wenn ich das Build über Jenkins gestartet habe. das habe ich dann noch kurz gefixed mit folgendem: (![executionRightsAdded](images/executionRightsAdded.png))

nach einigem hin und her konnte ich das Porjekt korrekt laufen lassen: (![JenkinsRunSuccess](images/JenkinsRunSuccess.png)) (![jenkinsWorkspace](images/jenkinsWorkspace.png))

desweiteren Habe ich das Nodejs Plug für Jenkins installiert: (![nodejsPlugin](images/nodejsPlugin.png))

auch zu meiner Umgebung habe ich NodeJS hinzugefügt: (![NodeJSEnv](images/NodeJSEnv.png))

einen Execute Shell welche beim Buildverfahren erfolgen soll hinzugefügt: (![shellExecute](images/shellExecute.png))

Danach habe ich das Projekt nochmal gebaut: (![buildWithNodeJS](images/buildWithNodeJS.png))

Zum Post Build habe ich noch die JUnit-Test hinzugefügt: (![JUnitTests](images/JUnitTests.png))

Als nächstes habe ich noch das Jacoco Plugin installiert: (![JacocoPlugIn](images/JacocoPlugIn.png))

Hier der Coverage Report zu sehen: (![JacocoCoverageReport](images/JacocoCoverageReport.png)) 