pipeline {
    agent { label 'si0vmc2837-static-agent' }
    stages {
        stage("git_checkout") {
            steps {
                echo "Cloning repository"
                git 'your_git_repository_url_here'
                echo "Repo cloned successfully"
            }
        }
    }
}
