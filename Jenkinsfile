pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        mail(subject: 'Starting', body: 'Your build is getting started', from: 'Vishnu', to: 'vgillell@gmail.com')
      }
    }
  }
}