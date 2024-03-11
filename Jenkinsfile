pipeline {
    agent any

    stages {
        // stage('clone') {
        //     steps {
        //        git branch: 'main', url: 'https://github.com/BALUOMKAR/terraformCI-CD.git'
        //     }
        // }
        stage('init') {
            steps {
                sh "terraform init"
            }
        }
    }
}
