# OpenShift Commands.






## Contents at a Glance.
* [About.](#about)
* [Documentation.](#documentation)
* [General.](#general)
* [oc get](#oc-get)
* [oc new-build](#oc-new-build)
* [oc start-build](#oc-start-build)
* [oc new-app](#oc-new-app)
* [oc expose](#oc-expose)
* [oc describe](#oc-describe)
* [oc scale](#oc-scale)
* [oc delete](#oc-delete)
* [oc adm](#oc-adm)
* [Help.](#help)





## About.





## Documentation.





## General.

| Key/Command                                                                                      | Description                                                                |
| ------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------- |
| oc cluster up                                                                                    |                                                                            |
| oc cluster down                                                                                  |                                                                            |
| oc login                                                                                         |                                                                            |
| oc login -u [USERNAME] -p [PASSWORD]                                                             |                                                                            |
| oc login -u system:admin                                                                         |                                                                            |
| oc logout                                                                                        |                                                                            |
| oc cluster up --public-hostname=SERVER_IP                                                        |                                                                            |
| oc status                                                                                        |                                                                            |
| oc whoami                                                                                        |                                                                            |
| oc whoami -t                                                                                     | Get token.                                                                 |
| oc whoami --token                                                                                |                                                                            |
|                                                                                                  |                                                                            |





## oc get

| Key/Command                                                                                      | Description                                                                |
| ------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------- |
| oc get projects                                                                                  |                                                                            |
| oc get users                                                                                     |                                                                            |
|                                                                                                  |                                                                            |





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





## oc adm

| Key/Command                                                                                      | Description                                                                |
| ------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------- |
| oc adm policy add-cluster-role-to-user cluster-admin [userName]                                  |                                                                            |
|                                                                                                  |                                                                            |





## Help.
