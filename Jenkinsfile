pipeline {
	agent any
	  stages {
	    stage ('docker-container')
                   {
		steps {
               sh " docker build -t httpd2:1.0 ."
	       sh "docker run -itdp 100:80 httpd2:1.0"

}
}

}

}
