pipeline {

    agent any
    tools {

        maven 'maven-default'

        jdk 'jdk-1.8'

    }

        stages {

        stage('clonecode') {
            steps {
                script {

                    deleteDir()

                    checkout scm

                    sh 'git checkout ${GIT_BRANCH}'

                    sh 'echo ${GIT_BRANCH}'


                }

            }

        }

}

}
