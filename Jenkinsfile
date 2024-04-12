pipeline {
    agent any
    
    stages {
        stage('Parallel Stage') {
                stage('numpay') {
                    steps {
                        echo 'Executing numpy code'
                        git 'https://github.com/Jhunter1402/PythonProgram-Jenkins-FreeStyle.git'
                        sh "python3.9 -m venv myvenv1"
                        sh "source myvenv1/bin/activate"
                        sh "pip3.9 install -r requirments.txt"
                        sh "python3.9 numpycode.py"
                        
                    }
                }
        }
    }
}
