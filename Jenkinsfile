node {
    stage("Clean up"){  
        sh "ls"
        echo "I want to get back stuff"
        sh "git status"
        sh "git pull"
        def new_image = docker.build("new_image")
    }
}