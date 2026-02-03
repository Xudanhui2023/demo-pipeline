pipeline {
    agent any
    stages {
        stage('查看日志') {
            steps {
                // 这样才能正确执行 Shell 命令
                sh 'docker logs jenkins'
            }
        }
    }
}
