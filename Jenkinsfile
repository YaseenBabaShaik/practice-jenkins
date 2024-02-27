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
    agent any
        stages {
            stage('test'){
                steps{
                    script{
                        env.abc = "Hello"
                        def xyz =10

                        print "abc = ${abc}"
                        print "xyz = ${xyz}}"

                        print abc

                        def new1() {
                            print "hello"
                        }
                        new1()
                    
                }
                script{
                    print "abc = ${abc}"
                }
            }
            }
            stage(test2) {
                steps{
                    script{
                        print "abc =${abc}"
                    }
                }

            }
    }
}