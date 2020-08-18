pipeline {
    agent any
    tools { 
      'Maven 3.3.9'
      'Jdk8'
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
