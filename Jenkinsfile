node {

	stage('job name'){

		job: 'Build_Pipeline'
		description: 'Build the job using jenkinsfile'
	}

	stage('git clone'){

	     url: 'https://github.com/Srk-771/Test-Project.git'
	     branch: 'master'
	     poll: '* * * * *'
	}

	 stage('Maven_Build') {
    
             sh 'pom.xml, clean install'
        }
   
}
