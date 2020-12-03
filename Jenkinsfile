pipeline {
tools {
    maven 'M3'
  }
   agent { label 'master' }
options {
        skipStagesAfterUnstable()
    }
    stages {

        stage('Build3') {
            steps {
                sh 'mvn clean install'
            }
        }


      

 



       
    }
}
