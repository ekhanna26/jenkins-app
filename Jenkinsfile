node('workers') { 
try {
        stage('Checkout'){
            echo "Checking out"
}
        stage('Quality Test'){
            echo "Running quality tests"
}
        stage('Unit Test'){
            echo "Running unit tests"
}
        stage('Security Test'){
            echo "Running security checks"
}
        stage('Build'){
            echo "Building artifact"
}
        stage('Push'){
           echo "Storing artifact"
}
        stage('Deploy'){
            echo "Deploying artifact"
}
        stage('Acceptance Tests'){
            echo "Running post-integrations tests"
}
} catch(err) {
    echo "Handling errors" 
} 
finally {
       echo "Cleaning up"
    }
}