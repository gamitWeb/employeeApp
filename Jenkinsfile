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
            # serve with hot reload at localhost:8080
            # npm run dev

            # build for production with minification
            # npm run build

            # build for production and view the bundle analyzer report
            # npm run build --report
                    '''
                }
            }
        }
 }
}
