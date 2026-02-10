@Library ('jenkins-shared-library') _

def configMap = [
    project: "roboshop",
    component: "shipping",
]

if (env.BRANCH_NAME == 'main') {
    echo "Please follow the CR process"
}
else {
    javaEKSpipeline(configMap)
}