**Step 4:** Let us now set up the environment variables for Spark. Execute the following command to do so.

Run following commands to append the environment variable at the end of the file.

`echo "export SPARK_HOME=/usr/share/spark" >> ~/.bashrc`

`echo "export PATH=$PATH:$SPARK_HOME/bin:$SPARK_HOME/sbin" >> ~/.bashrc`

Now reload the modified .bashrc file using the following command.

`source ~/.bashrc`