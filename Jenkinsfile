pipeline {
    agent any
    environment {
        GITNAME = 'hansususu'
        GITMAIL = 'hansubin0039@gmail.com' 
        GITWEBADD = 'https://github.com/hansususu/fast-code.git'
        GITSSHADD = 'git@github.com:hansususu/fast-code.git'
        GITCREDENTIAL = 'git_cre'
        DOCKERHUB = 'hansususu/fast'
        DOCKERHUBCREDENTIAL = 'docker_cre'
    }
    stages {
        stage('start') {
            steps {
                sh "echo hello jenkins!!!"
            }
            post {
                failure {
                    sh "echo failed"
                }
                success {
                    sh "echo success"
                }
            }
        }
    }
}
