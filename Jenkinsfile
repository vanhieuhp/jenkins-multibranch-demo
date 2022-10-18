pipeline {
  agent {label 'slave1'}
  // options {
  //   buildDiscarder(logRotator(numToKeepStr: '5'))
  // }
  // stages {
  //   stage('Build') {
  //     steps {
  //       sh './gradlew clean check --no-daemon'
  //     }
  //   }
  // }
  // post {
  //   always {
  //       junit(
  //         allowEmptyResults: true, 
  //         testResults: '**/build/test-results/test/*.xml'
  //       )
  //   }
  // }

  stages {
    stage('hello jenkins') {
      steps {
        sh 'echo hello jenkins'
      }
    }
  }
}