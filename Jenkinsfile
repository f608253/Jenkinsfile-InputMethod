pipeline {
	agent any
	stages {
		stage ('build') {			
	input{
		message "Press Ok to continue"
		submitter "Manav,user2"
		parameters {
			string(name:'username', defaultValue: 'user', description: 'Username of the user pressing Ok')
		}
	}
	steps { 
		echo "User: ${username} said Ok."
	}
		}
	}
}
