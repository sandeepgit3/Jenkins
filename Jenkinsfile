pipeline {
    agent any
    tools { 
      Maven 'Maven'
      Jdk 'Jdk'
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
