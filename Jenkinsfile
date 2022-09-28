pipeline{
    agent{
        node{
            label "master"
            customWorkspace "/mnt/httpd"
        }
    }
    stages{
        stage ('deploy index '){
            steps {
			
				sh "sudo ansible-playbook play.yaml"
           
            }
        }
        
    }
    
}
