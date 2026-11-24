pipeline{
    agent any

    stages{
        stage("Git"){
            git(
                url:"",
                branch:"main",
            )
        }

        stage("Hello"){
            steps{
                echo "Hello Pipeline from Jenkins File"
            }
        }
    }
}