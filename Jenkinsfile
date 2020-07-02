pipeline {
  agent any
  stages {
    stage('Pull SCM') {
      environment {
        Branch = ''
      }
      steps {
        git(url: 'http://ferramentasgo.centralit.com.br:8080/scm/git/citsmart-itsm-enterprise', branch: 'master', credentialsId: 'kelvin.rocha')
      }
    }

  }
  environment {
    Branch = ''
  }
}