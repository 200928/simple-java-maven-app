pipeline {
    agent any  // 使用任何可用的 Jenkins 节点
    stages {
        stage('Build') { 
            steps {
                // 直接调用宿主机的 Maven 进行打包
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
