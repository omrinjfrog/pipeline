# Artifatory pipeline exapmle
This pipeline is a simple example of how to deploy file on Artifactory.
To use this repo please configure this repo in pipeline:
1) Add integration to pipeline that uses github (Token is genereted in github settings -> developer settings), integration name is 'githubtest' as in the yaml file found in configuration->gitProvider->resources
2) Add another integration in pipeline to artifatory called artifactory (see in yaml file) pipelines->steps-> integrations->name
3) Add pipeline sources to this repo

Step one in .yaml file is the one that deply the file to test repo. other steps are dummy
