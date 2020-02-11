# ta-datacollector

Install

Once downloaded, follow the steps below.

TIP: The Data Collector is likely to consume a significant amount of resources while gathering data therefore, we recommend you run the tool in a pre-production environment.
1
Copy and place the file to your system in a directory where it has read-write-execute access.
Then decompress the downloaded file:
tar xvfz transformationadvisor-Linux_<WORKSPACE_NAME>_<COLLECTION_NAME>.tgz

2
Go to the Data Collector directory:
cd transformationadvisor*
Run tool

Select your domain and analysis type below and run the generated command from the data collector directory to begin scanning.

./bin/transformationadvisor -w <WEBSPHERE_HOME_DIR> -p <PROFILE_NAME> [<WSADMIN_USER> <WSADMIN_PASSWORD> --scan-node --ignore-missing-binary --ignore-missing-shared-library --applications --applications-file]

The Data Collector will return a .zip file containing your data
