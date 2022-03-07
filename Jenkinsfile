pipeline {
    agent any
    options { checkoutToSubdirectory('foo') }
    stages {
        stage('Hello') {
            steps {
                echo 'hello'
            }
        }
    }
}
