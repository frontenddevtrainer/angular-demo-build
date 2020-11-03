pipeline {
    agent { label "Main" }
    
    stages {
            stage("install") {
                steps { sh 'npm install' }
            }
            
            stage("build") {
                steps { sh 'npm run build' }
            }
    }
}
