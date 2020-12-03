pipeline {
tools {
    maven 'M3'
  }
   agent { label 'master' }
options {
        skipStagesAfterUnstable()
    }
    stages {

        stage('Build5') {
            steps {
                sh 'mvn clean install'
            }
        }


      

 



       
    }
}
