pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                git 'https://github.com/alexandresjunior/liferay-sample-workspace.git'

                // Run Maven on a Unix agent.
                sh "blade gw initBundle"
            }
        }
    }
}
