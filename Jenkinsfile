pipeline{
    agent any
        stages
        {
            stage('build')
            {
                echo'building jenkins'
            }

             stage('Test')
            {
                echo'Testing jenkins'
            }
               stage('Test')
            {
                echo'Testing jenkinzzs'
            }
        }
        post
        {
            success
            {
                emailtext subject:"buildingpipeling",
                          boy:"hi",
                           to: 'moulik4815.be22@chitkara.edu.in',
                          attachLog: true
            }

            failure
            {
                emailtext subject:"build droped",
                          boy:"hi test failes",
                           to: 'moulik4815.be22@chitkara.edu.in',
                          attachLog: true
            }
        }

}
