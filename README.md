E-STUDY READ ME
This is an open source project to adap e learing system basic on plf frame work 
Compatible with tomcat download from jboss gatein 3.5.4 Final
Status 
[![Build Status](https://travis-ci.org/phamtuanchip/estudy.png)](https://travis-ci.org/phamtuanchip/estudy)

public page http://phamtuanchip.github.io/estudy
wiki page http://wiki.vfossa.vn/mhst:ideas:mhst2013:gatein01

integration build test https://travis-ci.org/phamtuanchip/estudy
Maven 3.0.4
Java  1.6.x
Tomcat application server 7
Eclipse for j2ee
Git client tool  

Quick run guide 
clone repository 
build with maven by : mvn clean install -s settings.xml

download gatein 3.5.4 final tomcat 7 bundle  from there https://docs.google.com/file/d/0Bw2eZ8CfkgNBOHZuN0hBNGhSVVE/edit?usp=sharing
copy service/target/estudy-service.jar  to tomcat/lib 
copy webui/target/estudy.war to tomcat/webapps
go to tomcat/bin and run command "gatein.sh run" for unix base (mac, linux) or "gatein.bat run" for windows  
login page http://localhost:8080/portal by root with pass gtn 
import all application in application registry page 
create new page and add estudy portlet to that page

for more detail and prectice you can enjoin this documentation http://docs.exoplatform.com/public/index.jsp?topic=%2FPLF40%2Fsect-Reference_Guide-Tutorials-Deploying_your_first_Portlet.html



