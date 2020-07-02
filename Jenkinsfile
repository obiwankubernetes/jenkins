// two types: declarative or scripted

// declarative
pipeline {
    // agent - where to execute
    agent any
    // where and what work to be done
    stages {

        stage("build") {

            steps {
                echo 'building the application ...'
            }

        }

        stage("test") {

            steps {
                echo 'testing the application ...'
            }

        }

        stage("deploy") {

            steps {
                echo 'deploying the application ...'
            }

        }
    }
}

// scipted
// node {
    // groovy script
// }