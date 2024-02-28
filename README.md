# TROUBLESHOOTS#
# JENKINS #######
# 128====IF YOU ARE NOT GIVEN ANY CREDENTIALS ( NO CREDENTIALS)
# 401, 403 === Wrong credentials
# 137 ==== out of memory error >> this kind of error in jenkins masters thats why we are make slaves for master{4gb} all pipelines in same master it will full up memory  >> slaves in ( VM'S)
# Docker not found # Mvn not found or not available  >> Scenario1 : this kind of errors should happen in > if the tool is installed but we are not defined in pipeline.# scenario 2: >> not installed 
# XMS === initial memory # XMX === max memory >> defined in pipeline  env ==
# sonar qube ( publish the sonarqube analysed reports )>> not reachable & unauthorized ( check token )    # nexus server(publish our artifacts ) >> unauthorized 401, 403 error ==if you get this kind of error you should check credentials .=======500 internal server error ==this kind error in minimal down time in that condition we are using restart,, then also its not working then you should  go on kubernetes  check pod  if the pod is up and running or not like that okay if there also pod is running but still my application is not working then you shouls do little bit troubkeshooting .
# jenkins also check logs from down side this best when compare to checking from upside logs .

