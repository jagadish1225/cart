pipeline{
    agent{
        label 'WORKSTATION'
    }

    triggers { 
        pollSCM('*/1 * * * *')
    }


    stages{
        
        stage('compile the code')     {
           steps{
            sh 'echo compile the code'
           }
        }


        stage('check the code quality')     {
           steps{
            sh 'echo code quality'
           }
        }

        stage('some test cases')     {
           steps{
            sh 'echo some test cases'
           }
        }
    }
}