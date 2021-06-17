pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'ls -a'
      }
    }

    stage('pwd') {
      steps {
        sh 'pwd'
      }
    }

    stage('mail') {
      steps {
        mail(subject: 'Test', body: 'Test Docker Jenkins', from: 'michael@buluma.me.ke', replyTo: 'michael@buluma.me.ke', to: 'michael@buluma.me.ke')
      }
    }

  }
}