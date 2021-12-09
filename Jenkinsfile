cat README.txt
pipeline {
    agent any
    stages {
        stage ('Git clone') {
            steps {
                
                dir ('testRepo') {
                    git url: "https://github.com/snehashingate/JenkinsfileRepo.git",
                        branch: "main"
                }
            }
        }
    }
}
