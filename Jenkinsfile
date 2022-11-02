pipeline {
	agent any
    stages {
        stage('Build on k8 ') {
            steps {  
		    
 
                       
                        sh '/usr/local/bin/helm repo add nginx-stable https://helm.nginx.com/stable'
		                    sh '/usr/local/bin/helm repo update'
                        sh '/usr/local/bin/helm install my-release nginx-stable/nginx-ingress'   
              			
            }           
        }
    }
}
