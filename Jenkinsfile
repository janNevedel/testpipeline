node ('master') {
  stage('Prepare') {
    git 'https://github.com/janNevedel/testpipeline.git'
    echo 'Testing build'
  }
  stage('Build') {
    openshiftBuild apiURL: '', authToken: '', bldCfg: 'cakephp-ex', buildName: '', checkForTriggeredDeployments: 'false', commitID: '', namespace: '', showBuildLogs: 'true', verbose: 'true', waitTime: '', waitUnit: 'sec'
  }
}
