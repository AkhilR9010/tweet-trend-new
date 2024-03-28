pipeline {
    agent {
        node{
            label 'maven'
        }
    }

    stages {
        stage('Hello') {
            steps {
                git branch: 'main', url: 'https://github.com/AkhilR9010/tweet-trend-new.git'
            }
        }
    }
}
