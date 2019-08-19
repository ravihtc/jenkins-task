node('docker') {
    stage('Clone Repo') {
        git 'https://github.com/ravihtc/jenkins-task.git'
    }
    stage('Make Docker Image') {
        sh '''
            cd web-image
            docker build -t ravihtc/web-image .
        '''
    }
}