pipeline {
    agent any
    
    stages {
        stage ('Excuting Maven Builds') {
            steps {
                sh 'mvn -f /var/lib/jenkins/workspace/multi-pipeline_master/webapp/pom.xml clean package'
            }
        }
  }
    
}
