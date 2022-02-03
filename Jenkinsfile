pipeline{
  agent: any
  stages{
    stage('Build'){
      steps{
        echo 'building...'
        sh './gradlew build --no-daemon'
        archiveArtifact artifact: 'dist/trainSchedule.zip'
      }
    }
  }
}
