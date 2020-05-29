pipeline{
    agent {label 'AzureAgent1'}
    stages {
        stage ('Source'){
            steps {
                git 'https://github.com/DummyReposJR/spring-petclinic.git'
            }
        }

        stage ('Package'){
            steps{
                sh 'mvn package'
            }
        }
    }
}

