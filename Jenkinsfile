pipeline{

  agent 'any'
  
stages {
        stage("NPM") {
            steps {
                script {
                    sh '''
						# install dependencies
            whoami
            #apt update -y
            #sudo su - jenkins
            node --version
            npm --version
            npm install --force
            # install ng
            ng install
            # Build the project
             ng build
             '''
                }
            }
        }
 }
}
