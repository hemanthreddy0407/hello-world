pipeline {
    agent any
    
    stages {
        stage ('Cloning Git Repo') {
            steps {
                sh 'rm -rf /var/lib/jenkins/workspace/multi-pipeline_master/hello-world/'
                sh 'git clone https://github.com/hemanthreddy0407/hello-world.git'
                ls '/var/lib/jenkins/workspace/pipeline3/hello-world/'
            }
        }
        stage ('Excuting Maven Builds') {
            steps {
                sh 'mvn -f /var/lib/jenkins/workspace/multi-pipeline_master/hello-world/webapp/pom.xml clean package'
            }
        }
  }
    
}
