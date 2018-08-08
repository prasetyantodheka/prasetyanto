pipeline {
  agent any
  stages {
    stage('Run') {
      environment {
        test = 'test'
      }
      steps {
        sh '''git status
pwd'''
        sleep 10
      }
    }
    stage('report') {
      steps {
        mail(subject: 'test', body: 'test', from: 'prasetyanto.dheka01@gmail.com', to: 'prasetyanto@dropsuite.com')
      }
    }
  }
}