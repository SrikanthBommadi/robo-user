@Library('jenkins-shared-library')_

def configMap = [
    project: "roboshop",
    component: "user"
]

if ( ! env.BRANCH_NAME.equalsIgnoreCase('main')){
    javaMavenEKSPipeline(configMap)
}
else{
    echo "Please follow production process"
}