def muni = 10
def hema = 20
def chitti = 30

node('hema') {
    stage('checkout') {
        sh "git checkout happens here"
        echo "hema ${hema}"
    }
    stage('configure') {
        sh "build configuration heppens here"
        echo "muni ${muni}"
    }
    stage('build') {
        sh "code compilation happens here"
        echo "chitti ${chitti}"
    }
    stage('package') {
        sh "pkg happens here"
    }
}
