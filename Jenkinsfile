node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'abdelrahmanbelal') {

        def customImage = docker.build("abdelrahmanbelal/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}