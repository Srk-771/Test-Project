node {

	stage('job name'){

		job: 'Build_Pipeline'
		description: 'Build the job using jenkinsfile'
	}

	stage('git clone'){

	     url: 'https://github.com/Srk-771/test-project-1.git'
	     branch: 'master'
	     poll: '* * * * *'
	}

	 stage('Maven_Build') {
    
             sh 'maven -f pom.xml, clean install'
        }
   
}
