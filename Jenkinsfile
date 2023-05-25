
def branchName1
pipeline {
    agent any
  
    stages {
        stage("show branch"){
            steps {
                script {
                    def branchv1 = env.GIT_BRANCH
                    branchName1 = branchv1.substring("origin/".length())
                    echo "Branch name v7:${branchName1}"
                }
            }
        }
        stage("Build jar") {
            steps {
                echo "Buildinfrfrg the applicatiod v vddd.."
               
            }
        }
        stage("Build image") {
            steps {
                echo "ddddBuilding the Docker imageccc...ggggg "
               
            }
        }
        stage("Deploy app") {
            steps {
                echo "Deploying the application..."
                echo "dddheldldddo toddddddddceddfffddddcfdddfffvvvv "
            }
        }
    }
}
