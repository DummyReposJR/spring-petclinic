node {
    stage ('scm')
    {
        git 'https://github.com/DummyReposJR/spring-petclinic.git'

    }

    stage ('build'){
        sh 'mvn package'
    }


}