pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        withGradle() {
          sh '''sudo chmod +x gradlew
./gradlew -version
./gradlew clean
./gradlew build'''
        }

      }
    }

  }
}