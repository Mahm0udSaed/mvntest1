pipeline {
tools {
    maven 'M3'
  }
   agent { label 'master' }
options {
        skipStagesAfterUnstable()
    }
    stages {

 stage('source') {
            checkout scm
        }

        stage('Build338') {
            steps {
                sh 'mvn clean install'
            }
        }


      

 



       
    }
}
