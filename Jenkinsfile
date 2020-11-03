pipeline {
   
  agent { label "master" }
    
    stages {
            stage("install") {
                steps { sh 'npm install' }
            }
            
            stage("build") {
                steps { sh 'npm run build' }
            }
    }
}
