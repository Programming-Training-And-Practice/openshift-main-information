# OpenShift Commands.






## Contents at a Glance.
* [About.](#about)
* [Documentation.](#documentation)
* [General.](#general)
* [oc new-build](#oc-new-build)
* [oc start-build](#oc-start-build)
* [oc new-app](#oc-new-app)
* [oc espose](#oc-expose)
* [oc describe](#oc-describe)
* [oc scale](#oc-scale)
* [oc delete](#oc-delete)
* [Help.](#help)





## About.





## Documentation.





## General.





## oc new-build

| Key/Command                                                                                      | Description                                                                |
| ------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------- |
| oc new-build --strategy docker --dockerfile - --code . --name [nameApp] < .[pathToDockerfile]    |                                                                            |
|                                                                                                  |                                                                            |





## oc start-build

| Key/Command                                                                                      | Description                                                                |
| ------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------- |
| oc start-build --from-dir . [nameApp] --follow                                                   |                                                                            |
|                                                                                                  |                                                                            |





## oc new-app

| Key/Command                                                                                      | Description                                                                |
| ------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------- |
| oc new-app --image-stream [imageName] --name [appName]                                           |                                                                            |
|                                                                                                  |                                                                            |





## oc expose

| Key/Command                                                                                      | Description                                                                |
| ------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------- |
| oc expose svc [nameApp] --port=[numberPort]                                                      |                                                                            |
|                                                                                                  |                                                                            |





## oc describe

| Key/Command                                                                                      | Description                                                                |
| ------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------- |
| oc describe route [nameApp]                                                                      |                                                                            |
|                                                                                                  |                                                                            |





## oc scale

| Key/Command                                                     | Description                                                                |
| --------------------------------------------------------------- | -------------------------------------------------------------------------- |
| oc scale dc [nameProject] --replicas=[numberReplicas]           |                                                                            |
|                                                                 |                                                                            |





## oc delete

| Key/Command                                                     | Description                                                                |
| --------------------------------------------------------------- | -------------------------------------------------------------------------- |
| oc delete all -l app=[nameApp]                                  |                                                                            |
|                                                                 |                                                                            |





## Help.
