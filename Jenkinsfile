pipeline {
    agent any
    stages {
        stage("Build") {
                       when {
                          changeRequest( target: 'main')
                        }
            steps {
                echo "Hello World change Request"
              }
        }
    }
}
