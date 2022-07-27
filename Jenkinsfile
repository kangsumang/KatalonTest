pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh '''
                cd  /Users/erickasumang/Downloads/kse
                ./katalonc  -projectPath="/Users/erickasumang/Downloads/kse/SampleProject/SampleProject.prj" -browserType="Chrome" -retry=0 -statusDelay=15 -testSuitePath="Test Suites/New Test Suite" -apiKey="17357865-c27e-4dae-8fed-dbc6db9d2781"
                '''

            }

        }

    }

}
