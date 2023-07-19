pipeline {
  agent any
  stage {
    stage ['Build'] {
      steps {
        echo 'Running build automationnn'
        sh './gradlew build --no-daemon'
        archirveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
