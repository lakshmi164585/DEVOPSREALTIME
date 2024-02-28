# TROUBLESHOOTS#
# JENKINS  troubleshoot #######
# 128====IF YOU ARE NOT GIVEN ANY CREDENTIALS ( NO CREDENTIALS)
# 401, 403 === Wrong credentials
# 137 ==== out of memory error >> this kind of error in jenkins masters thats why we are make slaves for master{4gb} all pipelines in same master it will full up memory  >> slaves in ( VM'S)
# Docker not found # Mvn not found or not available  >> Scenario1 : this kind of errors should happen in > if the tool is installed but we are not defined in pipeline.# scenario 2: >> not installed 
# XMS === initial memory # XMX === max memory >> defined in pipeline  env ==
# sonar qube ( publish the sonarqube analysed reports )>> not reachable & unauthorized ( check token )    # nexus server(publish our artifacts ) >> unauthorized 401, 403 error ==if you get this kind of error you should check credentials .=======500 internal server error ==this kind error in minimal down time in that condition we are using restart,, then also its not working then you should  go on kubernetes  check pod  if the pod is up and running or not like that okay if there also pod is running but still my application is not working then you shouls do little bit troubkeshooting .
# jenkins also check logs from down side this best when compare to checking from upside logs .

# ########## git troubleshoot errors ##############
# s1: In previously our company we were using our own git that means we have set up git using like a docker image and we were using a like  a Docker image and we were using  it by a providing some amount of storage and some amount of memory okay same thing we used to provide to clients okay so most common issue obviously its going to be 128  that is like no credentials 
# 401 & 403 >> wrong credentials
# s2:not enough space 
# s3: push error >> it will happens when the pushing file is large and there is enough space in that condition we will get this error .=== increase post buffer for that post buffer commnad is also there in git
# s4: Merge conflicts::::::connect the person  for mutual agreement 
# s5: user/token is better way when compared to user and passwd for reducing  login issues.

# ###########sonarqube troubleshoot errors ########### 

# s1: -Dsonar.ProjectKey==k should be capital .....& ProjectName========= N should be capital
# s2:tool/sonar/bin/sonar-scanner>>> not found>> means it may be installed but not defined  or not defined
# s3:token should be always correct and also url 
# s4: Dsonar.Java.binaries>>> (java project) 
# s5:not reachable>>> means sonar is up and running or not
# s6: memory issue >>. if sonar is also like a source like project but if it does not having enough memory available or storage available it may not function well okay 
# s7: in case our sonarqube is deployed inside kubenetes so every quarter we use to upgrade sonar qube >>> that means we use LTS support version 
