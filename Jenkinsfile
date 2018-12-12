pipeline {

    agent any

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
