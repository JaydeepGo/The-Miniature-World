pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Hello1') {
            steps {
                script{
				EMAIL_TO = 'jaydeep415@gmail.com'   
				mail bcc: '', body: "This is an AUTO GENERATED Email. PLEASE DO NOT REPLY.<br><br>", cc: '', charset: 'UTF-8', from: '', mimeType: 'text/html', replyTo: '', subject: "HI", to: "${EMAIL_TO}"; 
	            }    
            }
        }
    }
}
