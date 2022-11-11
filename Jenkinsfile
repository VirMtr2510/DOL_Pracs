pipeline {
    agent any 
    parameters {
        string(name: 'FName')
        string(name: 'LName', defaultValue: 'Mhatre')
        choice(name: 'Classroom-Batch' , choices: ['TIET-A1','TIET-A2','TIET-B1','TIET-B2'])
        choice(name: 'Elective' , choices: ['Cyber','Green-IT'])
    }
    stages {
        stage('Hello'){
            steps{
                echo "Hello World"
            }
        }
        stage('FName') {
            steps {
                echo "First Name:  ${params.FName}"
            }
        }
        stage('LName') {
            steps {
                echo "Last Name:  ${params.LName}"
            }
        }
        stage('choice') {
            steps {
                echo "Classroom-Batch: ${params.Classroom-Batch}"
            }
        }
        stage('choice') {
            steps {
                echo "Elective: ${params.Elective}"
            }
        }
    }
}
