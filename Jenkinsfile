pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                dir('/Users/erickasumang/Downloads/kse'){
                    bat 'docker run -t --rm -v $(pwd)/SampleProject:/tmp/project katalonstudio/katalon katalonc.sh -projectPath=/tmp/project -browserType="Chrome" -retry=0 -statusDelay=15 -testSuitePath="Test Suites/New Test Suite" -apiKey="17357865-c27e-4dae-8fed-dbc6db9d2781"'
                }
            }
        }
    }
