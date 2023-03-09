pipeline {
    agent any
    
    stages {
        stage ('Cloning Git Repo') {
            steps {
                sh 'git clone https://github.com/hemanthreddy0407/hello-world.git'
            }
        }
        stage ('Excuting Maven Builds') {
            steps {
                sh 'mvn -f /var/lib/jenkins/workspace/multi-pipeline_master/webapp/pom.xml clean package'
            }
        }
  }
    
}
