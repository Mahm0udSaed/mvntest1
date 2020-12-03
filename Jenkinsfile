pipeline {
tools {
    maven 'M3'
  }
   agent { label 'master' }
options {
        skipStagesAfterUnstable()
    }
    stages {

        stage('Build6') {
            steps {
                sh 'mvn clean install'
            }
        }


      

 



       
    }
}
