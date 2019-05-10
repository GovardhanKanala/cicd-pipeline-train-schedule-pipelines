pipeline{
  agent any
     stages{
      stage ('Build'){
      steps{
      echo 'Running build automation'
      sh '.gradelw build --no-deamon'
      archiveArtifacts articats: '/dist/trainShedule.zip'
      
      }
      }
     }
}
