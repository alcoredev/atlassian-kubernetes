pipeline {
  agent any
  stages {
    stage('Autoscale Env post-deploy') {
      steps {
        sh '''curl -V
curl -u --insecure admin:admin https://test.pandanet.xyz/rest/api/2/serverInfo'''
      }
    }

  }
}