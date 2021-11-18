pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        echo 'Running build automation'
        sh './gradelew build --no-daemon'
        archiveartifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
