
node('nodejs') {
stage('Checkout') {
                    git branch: 'main',
                    url: 'https://github.com/ParvathiDevi/Do400-pipeline:'
}
stage('Backend Tests') {
sh 'node ./backend/test.js'
}
stage('Frontend Tests') {
sh 'node ./frontend/test.js'
}
}
