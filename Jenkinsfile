node {

    stage('Checkout') {
        echo 'Checking out source code...'
        checkout scm
    }

    stage('Build') {
        echo 'Installing dependencies...'
        bat 'npm install'

        echo 'Running Build...'
        bat 'npm run build'
    }

    echo 'Pipeline completed successfully.'
}