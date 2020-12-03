pipeline {
tools {
    maven 'M3'
  }
   agent { label 'master' }
options {
        skipStagesAfterUnstable()
    }
    stages {

        stage('Build80') {
            steps {
                sh 'mvn clean install'
            }
        }


      

 



       
    }
}
