## WIP

Custom jar for pushing shredded Snowplow part files in a HDFS into DashDB tables. Current iteration only facilitate movement of atomic-events part files into a DashDB 'events' table.


Build with Maven (mvn install)


Mandatory jar arguments:

\-\-dbhost \<DashDB Host (no port)\>

\-\-dbtable \<DashDB Table\>

\-\-dbuser \<DashDB Username\>

\-\-dbpassword \<DashDB Password\>

\-\-hdfspath \<Part Files folder in HDFS\>
