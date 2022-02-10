
pipeline {
    agent any
    stages {
        stage("Build") {
            when {
                expression {
                    BRANCH_NAME == 'dev'
                }
            }
            steps {
                echo 'building'
            }
        }
        stage("Deploy") {
            steps {
                echo 'deploying'
            }
        }
        stage("Test") {
            steps {
                echo 'testing'
            }
        }
    }
}

