# OC CLI Commands

* ## Login to openshift
     oc login https://api.preview.openshift.com --token=<your_session_token>

* ## oc get projects
     oc get projects

* ## switch to a project
     oc project <your_project_name>

* ## delete all completly from project
     oc delete all --all

* ## after delete all delete project
     oc delete project <project_name>

* ## set env for all pods
     oc set env pods --all --list
