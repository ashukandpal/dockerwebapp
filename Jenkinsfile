node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockernodejs') {

        def customImage = docker.build("ashishkandpal/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
