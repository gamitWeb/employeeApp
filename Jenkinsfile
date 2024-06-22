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

            #Install angular
            sudo npm install -g @angular/cli@15.2.9
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
