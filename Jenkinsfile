pipeline { 
    agent any 
    stages {
        stage('Clone Git') { 
            steps {
                git 'https://github.com/gaurang1235/pipeline_git.git' 
            }
        }
        stage('Build Code') {
            steps {
                sh "g++ demo.cpp"
            }
        }
        stage('Run') {
            steps {
                sh "./a.out"
            }
        }
    }
}
