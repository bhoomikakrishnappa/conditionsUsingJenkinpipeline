pipeline {
    agent any
    stages {
        stage("Test")
        {
            when {
                branch "main"
            }
            steps {
                echo "your in master branch"
            }
        }
    }    
}


