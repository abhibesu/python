I want to develop a software whose objective is to sense objects in s3 bucket/HDFS file system and start bundle, coordinator or workflow as per the requirement.
At the end of the project, I should be able to start bundle/coordinator/workflow as user choose to start.
I will gain much more understanding about the python design.

Design
1. The whole project will be configuration driven. Means user should be able to define -

	* If he/she wants to start bundle/coordinator/workflow
	* The parameters passed to the bundle/coordinator/workflow can be configurable

	* The software will have the intelligence ...(To be continued)


First Cut:
1. Start a bundle/coordinator/workflow sensing the data
2. Create a workflow template
3. Create a workflow generator
4. The code should be thoroughly unit tested
