pipeline{
    agent any

    stages{
        stage('build'){
            steps{
                echo "build start"
            }
        }

        stage('test'){
            steps{
               sh "python3 --version"
            }
        }
        stage('deploy'){
            steps{
               sh "python3 app.py"
            }
        }
    }
}
