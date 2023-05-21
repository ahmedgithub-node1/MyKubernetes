pipeline {

    agent any

    stages {

        stage("build") {

            steps {
                echo 'building my application...'
            }
        }

        stage("test") {

            steps {
                git 'https://github.com/ahmedgithub-node1/MyKubernetes.git'
            }
        }

        stage("deploy") {

            steps {
                echo 'deployimg my application...'
            }
        }
    }

} 