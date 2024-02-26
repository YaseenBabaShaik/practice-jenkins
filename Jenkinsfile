// pipeline {
//     agent any
//     stages{
        
//         stage("Build and Test"){
//             steps{
//                 echo "uild and Test"
//             }
//         }
//         stage("SIL"){
//             steps{
//                 echo "Integration Testing"
//             }
//         }
//         stage("Pre-Prod"){
//             steps{
//                 echo "Pre-Prod"
//             }
//         }
//         stage("Prod"){
//             steps{
//                 echo "Production"
//             }
//         }

//     }
// }

@Library('roboshop') _

pipeline {
    agent any{
        stages {
            stage('test'){
                steps{
                    script{
                        test()
                    }
                }
            }
        }
    }
}