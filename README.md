# udgram-CiCd
### Udgram project pipeline

the project devided into three parts:
1- frontend (s3)
2- backend (eb)
3- database (rds)
 
you can access frontend from this url:
http://udgram-front.s3-website-us-east-1.amazonaws.com/


 



###this how CircleCi pipeline works
1- when cicrclCi trigger the branch has updated with new commit it first it initat new workflow
2- setup system and app dependencies like nodejs,aws,eb ...
3- install frontend and backend packages
4- deploy frontend to S3 bucket
5- deploy and run backend on eb

###Docs
you can check more from docs screenshots of what services are used in this project;

