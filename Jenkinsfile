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
            #npm install -g @angular/cli@15.2.9
            ng version
            # Build the project
             ng build
            # Run the project
            ng serve
             '''
                }
            }
        }
 }
}
