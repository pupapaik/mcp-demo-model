pipeline {
  agent {
    docker {
      image 'pupapaik/webapp'
    }
    
  }
  stages {
    stage('build') {
      steps {
        mail(subject: 'pica', body: 'kokot', to: 'jpavlik@mirantis.com')
      }
    }
    stage('') {
      steps {
        echo 'message'
      }
    }
  }
}