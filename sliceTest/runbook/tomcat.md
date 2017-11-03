#*Alert:  CRITICAL: 'Tomcat is Running' on 'dt-029872b6b92f16f30.prod.slicetest.com'*

##step1: find the instance name
##step2: check the Instance status in Build chack tool.
 (This tool contains only auto sclaing groups instances only)
http://ops.slicetest.com/cgi-bin/buildnum.pl
If instance not found in the tool, please go with next step
##step3: check Instance status 2/2 check in AWS console.
if  instance check (nstance reachability check failed)  1/2 i.e instance not launched properly.
So please inform component owner and  based on the component owner confirmation restart the instance
https://docs.google.com/spreadsheets/d/1DY7rOoAFeaoEyf7BM-oXS0zRM2GRZZx8So2foIOocGc/edit#gid=0
##step4: if Instance status 2/2 check passed.
login in to instance check the tomcat service status.
__]#/etc/init.d/tomcat7 status__
if service is not running, please inform the component owner.
NOTE: if you had any unexpected issue/challengs please check with avilable OPS team.
http://wiki.slicetest.com/Ops

