String teststring = "no"

if (teststring == "no") {
    pipeline {
            stage('Example') {
                echo 'Hello World'
                echo String.join(", ", currentBuild.getBuildCauses());
            }
    }
} 
