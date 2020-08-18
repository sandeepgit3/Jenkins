pipeline {
    agent any
    tools { 
        'Maven' 
        'Jdk' 
    }
}
    stages {
        stage ('Initialize') {
            steps {
                sh '''
                    echo "PATH = ${PATH}"
                    echo "M2_HOME = ${M2_HOME}"
                ''' 
            }
        }
    }
