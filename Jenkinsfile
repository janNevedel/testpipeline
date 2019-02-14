node ('master') {
  stage('Prepare') {
    git 'https://git.elostech.cz/jan.nevedel/myapp-cicd.git'
    echo 'Testing build'
  }
  stage('Build') {
    openshiftBuild apiURL: '', authToken: '', bldCfg: 'cakephp-ex', buildName: '', checkForTriggeredDeployments: 'false', commitID: '', namespace: '', showBuildLogs: 'true', verbose: 'true', waitTime: '', waitUnit: 'sec'
  }
}
