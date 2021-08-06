pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
            git url:'https://github.com/mydemo2020/test.git'
                echo 'Hello World'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
