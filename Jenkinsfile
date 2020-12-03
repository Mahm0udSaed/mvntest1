pipeline {
tools {
    maven 'M3'
  }
   agent { label 'master' }
options {
        skipStagesAfterUnstable()
    }
    stages {

        stage('Build1') {
            steps {
                sh 'mvn clean install'
            }
        }


      

 



       
    }
}
