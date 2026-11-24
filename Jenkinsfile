pipeline{
    agent any

    stages{
        stage("Git"){
           steps{
             git(
                url:"https://github.com/Abuappash/Jenkins-Jenkinsfile.git",
                branch:"main",
            )
           }
        }

        stage("Hello"){
            steps{
                echo "Hello Pipeline from Jenkins File"
            }
        }
        Stege ("Git Pulgin"){
            steps{
                echo "Git connect successfully"
            }
        }
    }
}