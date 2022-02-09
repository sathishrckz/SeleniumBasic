pipeline{
    agent any

    stages{
        stage('Build Stage'){
            steps{
            sh 'gradle clean build'
            }

        }
         stage('Tests Stage') {
                    steps {
                        gradlew('test')
                    }
           }

    }

}
