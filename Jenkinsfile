pipeline {
    agent any
    options { checkoutToSubdirectory('foo') }
    stages {
        stage('Hello world') {
            steps {
                echo 'world'
            }
        }
    }
}
