pipeline {
    agent any
    stages {
        stage('Example'){
            steps{
                echo 'Hello world'
            }
            steps {
                script {
                    def browsers = ['chrome', 'firefox']
                    for (int i = 0; i < browsers.size(); ++i) {
                        echo "Testing the ${browsers[i]} browser"
                    }
                }
            }
        }
    }
}