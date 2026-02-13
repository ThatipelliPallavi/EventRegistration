pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                publishHTML([allowMissing: false, alwaysLinkToLastBuild: false, icon: '', keepAll: false, reportDir: 'simple_event_registration_form.html', reportFiles: 'simple_event_registration_form.html', reportName: 'HTML Report', reportTitles: '', useWrapperFileDirectly: true])
            }
        }
    }
}
