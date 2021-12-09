pipeline {
    agent any
    stages {
        stage ('Git clone') {
            steps {
                
                dir ('JenkinsfileRepo') {
                    git url: "https://github.com/snehashingate/JenkinsfileRepo.git",
                        branch: "main"
                }
            }
        }
    }
}
