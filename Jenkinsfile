pipeline {
    agent {
        node {
            
            label 'maven'
        }
    }

    stages {
        stage('clone-code') {
            steps {
                git branch: 'main', url: 'https://github.com/vk1855/tweet-trend-new.git'
            }
        }
    }
}
