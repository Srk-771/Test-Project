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

    stage('Build Application') {
    
          echo 'Hello World'
    }
    stage('Deploy'){
           
         echo 'good Morning'       
              
    }
    stage('Create Tomcat Docker Image'){
           
        echo 'sharuk'
        echo 'Hello Sharuk'
    }    

}
