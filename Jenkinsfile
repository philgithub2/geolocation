pipeline{
    agent any
    tools{
        maven 'M2_HOME' 
    }
    stages {
        stage('maven Build') {
            steps {
                sh 'mvn clean install package'
            }
        }
    }        
}