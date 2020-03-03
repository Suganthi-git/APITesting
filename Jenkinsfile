node {
        stage('Checkout') {
            git url: 'https://github.com/Suganthi-git/APITesting.git',  branch: 'suganthi'
            echo '****************CHECKOUT SUCCESSFUL****************'
        }
       

       
			
	stage('Build') {
		def mvn_version = 'Maven_Home'
		withEnv( ["PATH+MAVEN=${tool mvn_version}/bin"]) {
			sh 'mvn site'
			}
		}
}
