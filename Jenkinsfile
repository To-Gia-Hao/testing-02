node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("To-Gia-Hao/testing-02")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
