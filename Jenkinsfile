pipeline {
  agent none
  stages {
    stage('AWS Deployment') {
      steps {
            sh '''
               terraform init
               terraform apply
            '''
        }
    }
  }
}