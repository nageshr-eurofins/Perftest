# Perftest
1. Install jenkins
2. Createa GIt Hub space
3. Creatae sample project --> Type freestyle project
4. Provide Git hub url in General section --> source code management-->.git url with credentials
5. Build trigger Git hub hook trigger for git scm Polling
Save

## Making Public IP using ngrok
1. download NGROK--unzip-->ran command ./ngrok http8080 --> public acessablie link for localhost:8080
2. Convert ip address of jenkins meachine to publi url using NGrok
Run command ./ngrok http 8080 ,it will give one http URL ..wait for some time
3. use ng rok url in github without 8080 in webhook and sestablish connection to jenkins
4. do changes to the code an commit
5. lookout for the build in junkins server

