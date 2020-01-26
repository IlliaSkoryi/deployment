pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        withGradle() {
          sh '''chmod +x gradlew
./gradlew -version
./gradlew clean
./gradlew build'''
        }

      }
    }

  }
}