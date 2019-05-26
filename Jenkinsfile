def muni = 10
def hema = 20
def chitti = 30

node('hema') {
    stage('checkout') {
        echo "git checkout happens here"
        echo "hema ${hema}"
    }
    stage('configure') {
        echo "build configuration heppens here"
        echo "muni ${muni}"
    }
    stage('build') {
        echo "code compilation happens here"
        echo "chitti ${chitti}"
    }
    stage('package') {
        echo "pkg happens here"
    }
}
