pipeline{
    agent{
        label 'WORKSTATION'
    }

    triggers { 
        pollSCM('*/5 * * * *')
    }


    stages{
        
        stage('compile the code')     {
           steps{
            sh 'compile the code'
           }
        }


        stage('check the code quality')     {
           steps{
            sh 'code quality'
           }
        }

        stage('some test cases')     {
           steps{
            sh 'some test cases'
           }
        }
    }
}