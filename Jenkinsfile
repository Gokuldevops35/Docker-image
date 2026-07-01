node {

    stage('Checkout') {
        git branch: 'main',
            url: 'https://github.com/Gokuldevops35/Docker-image.git'
    }

    stage('Check Docker') {
        sh 'docker --version'
    }

    stage('Pull Ubuntu Image') {
        sh 'docker pull ubuntu:22.04'
    }

    stage('Show Images') {
        sh 'docker images'
    }
}