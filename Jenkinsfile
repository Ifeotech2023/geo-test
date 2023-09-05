 pipeline{
    agent any 
    tools{
        maven 'M2_HOME'
    }
    stages{
    stage('maven clean'){
        steps{
         sh 'maven clean' 
        }
    }
    stage('maven install'){
        steps{
        sh   'maven install'
        }
    }
    stage('maven package'){
        steps{
            sh 'maven package'

    }

}
    }
 }
 