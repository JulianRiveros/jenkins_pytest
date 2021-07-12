pipeline{
    agent any
    stages {
        stage("testing"){
          steps{
                sh 'pip install pytest'
                sh 'python -m pytest -v'
          }
        }
    }
}
