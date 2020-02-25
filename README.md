# Perftest
Install jenkins
Createa GIt Hub space
Creatae sample project --> Type freestyle project
Provide Git hub url in General section --> source code management-->.git url with credentials
Build trigger Git hub hook trigger for git scm Polling
Save
download NGROK--unzip-->ran command ./ngrok http8080 --> public acessablie link for localhost:8080
Convert ip address of jenkins meachine to publi url using NGrok
use ng rok url in github without 8080 in webhook and sestablish connection to jenkins
do changes to the code an commit
lookout for the build in junkins server
