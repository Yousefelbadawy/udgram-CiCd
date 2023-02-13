# Udgram CI/CD Pipleline


###This how CircleCi pipeline works
1- when cicrclCi trigger the branch has updated with new commit it first it initat new workflow
2- setup system and app dependencies like nodejs,aws,eb ...
3- install frontend and backend packages
4- deploy frontend to S3 bucket
5- deploy and run backend on eb
