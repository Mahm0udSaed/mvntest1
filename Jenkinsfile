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
steps {
            checkout scm
}
        }

        stage('Build338') {
            steps {
                sh 'mvn clean install'
            }
        }


      

 



       
    }
}
