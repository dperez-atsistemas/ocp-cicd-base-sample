node {
  stage('build & deploy') {
    openshiftBuild bldCfg: 'hellopythonapp',
      namespace: 'development',
      showBuildLogs: 'true'
    openshiftVerifyDeployment depCfg: 'hellopythonapp',
      namespace: 'development'
  }