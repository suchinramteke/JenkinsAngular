pipeline{
    agent any

    stages{
        stage('build'){
            when{
                branch 'master'
                // changeset "**"
            }
            steps{
                echo 'Step build'
            }
        }
         stage('test'){
            steps{
                echo 'Step test'
            }
        }
         stage('package'){
            steps{
                echo 'Step package'
            }
        }
    }

    post{
        always{
            echo 'This is pipeline run is completed '
        }
    }

}