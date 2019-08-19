node('docker') {
    stage('Make Docker Image') {
        sh '''
            cd web-image
            docker build -t ravihtc/web-image .
        '''
    }
}