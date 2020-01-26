pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        withGradle() {
          sh '''./gradlew -version
./gradlew clean
./gradlew build'''
        }

      }
    }

  }
}