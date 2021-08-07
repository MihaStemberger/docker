Example of infinite artifact deployment to Wildfly. A wildfly_redeploy.war is already added to _deployables
folder but if you want to rebuild it just run 'mvn clean package'.
When the war file is in the _deployables, run 'docker-compose up'. On Windows 10 the artifact will infinitely redeploy.
