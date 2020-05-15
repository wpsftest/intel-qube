# www-sonarqube

<b>This is a Quality Rules READ ONLY Instance. Digital Marketing Engineering Developers DONOT push their code to this instance. </b>

WWW Sonar Qube Instance on Heroku : <a>https://www-sonarqube.herokuapp.com</a> 


<b>Steps for deploying sonarqube container on heroku</b>

1. heroku container:login
2. heroku create -a www-sonarqube
3. heroku container:push web -a www-sonarqube
4. heroku container:push web -a www-sonarqube
5. heroku container:release web -a www-sonarqube

Note: We are spinning up community version of sonarqube instance for limited period until CICD provide us with Enterprise Edition SonarQube. 

<b>Capablities</b>

1. Able to inject all WWW Project Definitons 
2. Able to inject all WWW Project code quality plugins
3. Able to inject all WWW Project code quality rules
4. Able to inject all WWW Project quality thresholds

Note: WWW Dev's will be pointing their Intellij sonarlint to this instance and cross check their code quality and once we get EE SonarLint we will be rolling out build breakers. 



