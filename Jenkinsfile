pipeline {
    agent any

    stages {
        stage('build the restration site') {
            steps {
                publishHTML([allowMissing: false, alwaysLinkToLastBuild: false, icon: '', keepAll: false, reportDir: '', reportFiles: 'registration.html', reportName: 'HTML Report', reportTitles: '', useWrapperFileDirectly: true])
            }
        }
    }
}
