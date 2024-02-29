pipeline {
    agent any

    stages {
        stage('Restaurant Dashboard Repo') {
            steps {
                echo 'cloning repo'
                git credentialsId: '3eba55f5-842a-433e-86bf-aa27f3cd4d64', url: 'https://github.com/jandivit143/RestaurantDashboard'
                echo 'repo cloned'
            }
        }
    }
}
