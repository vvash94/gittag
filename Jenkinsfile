// Powered by Infostretch 

timestamps {

node () {

	stage ('test - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'b810dce0-9b18-4161-bdbc-fbe1fac37804', url: 'https://github.com/vvash94/gittag.git']]]) 
	}
	stage ('test - Build') {
 			// Shell build step
sh """ 
echo "hello" 
 """ 
	}
}
}