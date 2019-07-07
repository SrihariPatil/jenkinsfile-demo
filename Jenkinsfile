pipeline {
    agent any
    stages {
        stage('Example'){
            steps{
                echo 'Hello world'
                script {
                    def browsers = ['chrome', 'firefox']
                    for (int i = 0; i < browsers.size(); ++i) {
                        echo "Testing ${browsers[i]} browser"
                    }
                }
            }
        }
    }
}