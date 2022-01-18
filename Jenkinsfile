pipeline{
agent any
  stages{
    stage('Build Stage'){
      steps{
        echo "Running the build Stage"
        sh ./gradlew build
        archieveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
  
}
