pipeline {
    agent any
    stages {

        stage('testing pipeline'){
          steps{
		    echo 'test1'
			    sh 'rm -rf from-jenkins'
				sh 'mkdir from-jenkins'
                sh 'touch from-jenkins/test.txt'
                }
        }

}
}