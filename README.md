*Hadoop On-Premise Templates*
=============


Hadoop On-Premise (Linux Job) for Automation Engine
http://github.com/Automic-Community/Hadoop-On-Premise-Templates

<!-- List of attached files -->
Contents of Solution Package:

						
								*hadoop_on-premise_templates.zip
								
								*Hadoop On-Premise Template job descriptions.pdf
								
								*hadoop_on-prem-image1.jpg
								
								*hadooop_on-prem-image2.jpg
								
						


Documenation and Instructions
---

<h1>On-Premise Linux Job Templates for running Hadoop Jobs - Hive, Pig, and Sqoop</h1>
<p>&nbsp;</p>
<p>These templates are provided to you as is. There is no support for these templates. Additionally, Automic holds no liability for their use. We ask if you improve on them that you share those improvements with the community. If you have any questions on these templates, please use the Community to discuss them.</p>
<p>Exports contain examples for Hadoop installed as a Linux/Unix Cluster. All of the templates rely on the Linux/Unix OS Agent. They assume you are running the agent on a box that has access to the the cluster. These templates use FileList and SQLi Variables. We use a best practice of putting the prompt set on a workflow definition rather than directly on the objects which allows you to quickly swap jobs from say a Windows box into the workflow without having to recreate the prompt set. Use the JOBP when assembling a workflow.</p>
<p>&nbsp;</p>
<h2><a id="hive-job-to-execute-a-hive-script" class="anchor" href="#hive-job-to-execute-a-hive-script"><span class="octicon octicon-link"></span></a>Hive job to execute a Hive Script</h2>
<p>TEMPLATE.HIVE.RUN_SCRIPT</p>
<p>To configure for your environment: Edit the Agent, Login and Path parameters to fit your environment. Edit the 'HADOOP_SCRIPT_LIST' variable object to point to the directory that contains your Hive Scripts.</p>
<p>&nbsp;</p>
<h2><a id="pig-job-to-execute-a-pig-script" class="anchor" href="#pig-job-to-execute-a-pig-script"><span class="octicon octicon-link"></span></a>Pig Job to execute a Pig Script</h2>
<p>TEMPLATE.PIG.RUN_SCRIPT</p>
<p>To configure for your environment: If you didn't do this already for your Hive scripts, edit the 'HADOOP_SCRIPT_LIST' variable object to point to the directory that contains your Hive Scripts. Edit the Agent, Login, and Path parameters to fit your environment.</p>
<p>&nbsp;</p>
<h2><a id="hdfs-jobs" class="anchor" href="#hdfs-jobs"><span class="octicon octicon-link"></span></a>HDFS Jobs</h2>
<p>CHECK_FILE (Use this like you would a file event in HDFS), LIST_FILES, DELETE_A_FILE, DELETE_DIRECTORY_ALL, TRANSFER_FROM_LOCAL_UNIX, TRANSFER_TO_LOCAL_UNIX</p>
<p>No customization needed for these jobs.</p>
<p>&nbsp;</p>
<h2><a id="sqoop" class="anchor" href="#sqoop"><span class="octicon octicon-link"></span></a>Sqoop</h2>
<p>IMPORT, EXPORT</p>
<p>To configure for your environment: We only created one Sqoop job for mySQL as an example. If you are using a different database, you need to change the connection string syntax.</p>
<p>Make sure that the mySQL JDBC driver is in the correct path and the agent on the machine where the job is running is able to access the mySQL database server.</p>

Copyright and License
---

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)


Questions or Need Help? 
---
Join the [Automic Community Integrations](https://community.broadcom.com/communities/community-home?CommunityKey=83e49dd4-b93e-464a-a343-2bb1e51c13ec) to discuss this integration.
