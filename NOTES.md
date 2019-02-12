## Commands
### Custom
```
oc login -u 'muhammad.korejo-perficient.com' -p $OPENSHIFT_PASSWD -s https://master.na311.openshift.opentlc.com --insecure-skip-tls-verify
oc new-project 6a75-jenkins --description 'My Jenkins project for the OpenShift Advanced Developer Homework'
```

### Homework
```
./bin/setup_projects.sh 6a75 muhammad.korejo-perficient.com true
```