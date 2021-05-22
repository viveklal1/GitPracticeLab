pipeline {
    agent any
    NEW_VERSION= '1.2.0'
    stages {
        stage("build") {
            steps {
               echo "Building the application..."
                echo "building new version ${NEW_VERSION}"
                }
            }
        stage("test") {
            steps {
               echo "Testing the application..."
                }
            }
        stage("deploy") {
            steps {
                echo "Deploying the application..."
                }
            }
        }
    post {
        always {
            // Executes unconditionally after every build. 
        }
        Success {}
        failure{}
    }
  }

