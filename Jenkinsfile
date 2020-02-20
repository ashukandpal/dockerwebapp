node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockernodejs') {

        def customImage = docker.build("ashishkandpal/nodejsiteration3test")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
