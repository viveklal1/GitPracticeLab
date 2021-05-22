pipeline {
    agent any
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
     }

