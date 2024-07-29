# SRE-Project

As a Site Reliability Engineer, you have been tasked to automate the process of taking backups and saving them in an S3 bucket in your company’s AWS Account.
-Backups are taken every Friday after working hours
-Write a bash script to automate this process
-Set a cronjob to run the script on schedule
-You should receive an email notification at every stage of the backup process(Backup started, backup successful or failed)
-You can get creative by implementing S3 event notification to prompt system admins of an object upload in the S3 bucke
