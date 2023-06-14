String teststring = "no"

if (teststring == "no") {
    pipeline {
            stage('Example') {
                echo 'Hello World'
                int size = currentBuild.getBuildCauses().size()
                echo currentBuild.getBuildCauses().toArray(new String[size])
            }
    }
} 
