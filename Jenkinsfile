pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'write_file'
				script {
					write_file_path = "${env.WORKSPACE}/testdata/write.txt"
					file_contents = "Hello Anthony!! 這是一個測試例子"
					//write into write.txt
					writeFile file: write_file_path, text: file_contents, encoding: "UTF-8"
					// read file and print it out
					fileContents = readFile file: write_file_path, encoding: "UTF-8"
					println fileContents
				}
            }
        }

    }
}
