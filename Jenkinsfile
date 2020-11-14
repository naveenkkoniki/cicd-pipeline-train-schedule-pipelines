node {
   
   stage('Preparation') { 
      git 'https://github.com/naveenkkoniki/cicd-pipeline-train-schedule-pipelines.git'
   }
   
   stage('Build') {
         sh "./gradlew build"
      }
   
   stage('Results') {
      archive 'dist/trainSchedule.zip'
   }
}
