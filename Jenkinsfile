pipeline {
    agent any
    parameters {
      choice choices: ['CAMEROON', 'USA ', 'BENIN'], description: 'What is your country?', name: 'COUNTRY'
      string defaultValue: 'DETERGENT', description: 'What is your soap\'s name?', name: 'SOAP'
    }


    stages {
        stage('build') {
        when {
            expression {
            env.COUNTRY == 'USA'    //this will run if the cdt fits app equal to odilia

            }
        }
         
            steps {
                echo 'Hello World'
            }
        }



        stage('test') {
            steps {
                echo 'Hello World'
            }
        }
    
    
    
        stage('deploy') {
            steps {
                echo 'Hello World'
            }
        }
    
    
    
    
    
    
    
    
    
    }
 
}   
