This project holds the static api documentation for the portal release along with any downloadable resources we'd like to provide to potential users.

generate the api docs from the portal project here: https://github.com/PortalDB/Portal.git
use these commands for the jar and assembled jar: 
sbt doc

Then you can drop the resulting files into this project, overwriting whatever was there.

Other files we host here:
portal_2.11-1.0.jar (generated from the same project via sbt package, and dropped into the root directory)
portal-assembly-1.0.jar (same story, but using sbt assembly)
docker-compose.yml (a sample docker compose file for those using our canned portal/zeppelin container on Docker Hub)
