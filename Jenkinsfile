pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git url: 'https://github.com/venkatasivaeidiko/git-tuts.git', branch: 'master'
            }
        }
        stage('Build') {
            steps {
                echo "Build step..."
            }
        }
    }
}
