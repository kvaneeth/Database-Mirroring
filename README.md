# Database-Mirroring
These scripts will take copy of complete DB and sends the weekly data to backup DB through a cron job as scheduled.
Here We have used stored procedures/functions to send the data from the source to mirror DB.
We have used DB link to connect the source database and creating a temporary table to insert the data,then move the temp table to destination table in another database.
we an make it these scripts to send the data to remote databases too.
calling the functions/SP's in Shell Script and scheduled through cron.
