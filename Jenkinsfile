pipeline {
   
  agent { label "master" }
    
    stages {
            stage("install") {
                steps { bat 'npm install' }
            }
            
            stage("build") {
                steps { bat 'npm run build' }
            }
    }
}
