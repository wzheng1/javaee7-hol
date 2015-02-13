# Running the sample app
1. run steps 1-9 from the regular sample-app here:
https://github.com/openshift/origin/blob/master/examples/sample-app/README.md
1. run "osc process -n test -f application-template-jeebuild.json | osc create -n test -f -"   (using the template json from the app repo)
1. run "osc start-build -n test jee-sample-build"
1. run steps 15-18 from the regular sample-app readme
  * the app url is http://<ip address from 'osc get services -n test'>:8080/movieplex7-1.0-SNAPSHOT/

