# sp_ClusterInfo
<a name="header1"></a>

# Navigation
- [How to install the script](#how-to-install-the-script)
- [How to use the stored procedure](#how-to-use-the-stored-procedure)
- [License MIT](#license)
 
 
This is a stored procedure that you can install on your database servers so that you can easily retrieve the following cluster information:
1. Instance Name
2. All the server (cluster node) name/s
3. Is the instance Standalone or Clustered
4. If Clustered, which node is Active/Primary and Passive/Secondary
4. If Clustered, is it using Always On Availability Group (AG), Failover Cluster Instance (FCI) or combination of FCI and AG
5. If using Availability Group, it displays Availability Group Name and Listener Name.
6. SQL Server version and patch level, this will allow you to check the version and patch level of each nodes.

## How to install the script

It is recommended that you install this in the master database.
You can also install this stored procedure in other databases if you want to.

[*Back to top*](#header1)

## How to use the stored procedure

Run sp_ClusterInfo using the master database or the database where you installed the stored procedure.

Parameter/s:
* @Help = 1 - displays the help information. 

[*Back to top*](#header1)

## License

[The stored procedure, sp_ClusterInfo uses the MIT License.](LICENSE.md)

[*Back to top*](#header1)
