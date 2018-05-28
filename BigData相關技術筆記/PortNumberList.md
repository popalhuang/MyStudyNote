### Hadoop 2.7.2/3.0.0 環境用到的Port Number List:

<table border="2">
   <tr>
      <td>Service</td>
	  <td>Parameter</td>
      <td align='center'>Hadoop 2.7.2 Port</td>      
	  <td align='center'>Hadoop 3.0.0 Port</td>
   </tr>
	<tr><td rowspan='3'>NameNode</td><td>fs.defaultFS</td><td align='right'>8020</td><td align='right'>8020</td></tr>	
	<tr><td>dfs.namenode.http-address</td><td align='right'>50070</td><td align='right'>9870</td></tr>
	<tr><td>dfs.namenode.https-address</td><td  align='right'>50470</td><td align='right'>9871</td></tr>
	<tr><td rowspan='2'>Secondary NameNode</td><td>dfs.secondary.http.address</td><td  align='right'>50090</td><td align='right'>0000</td></tr>	
	<tr><td>dfs.secondary.https.address</td><td align='right'>50495</td><td  align='right'>0000</td></tr>
	<tr><td rowspan='4'>DataNode</td><td>dfs.datanode.address</td><td align='right'>50010</td><td align='right'>0000</td></tr>
	<tr><td>dfs.datanode.ipc.address</td><td align='right'>50020</td><td align='right'>0000</td></tr>
	<tr><td>dfs.datanode.http.address</td><td align='right'>50075</td><td align='right'>0000</td></tr>
	<tr><td>dfs.datanode.https.address</td><td align='right'>50475</td><td align='right'>0000</td></tr>	
	<tr><td rowspan='5'>ResourceManager</td><td>yarn.resourcemanager.scheduler.address</td><td align='right'>8030</td><td align='right'>0000</td></tr>
	<tr><td>yarn.resourcemanager.resource-tracker.address</td><td align='right'>8031</td><td align='right'>0000</td></tr>
	<tr><td>yarn.resourcemanager.address</td><td align='right'>8032</td><td align='right'>0000</td></tr>
	<tr><td>yarn.resourcemanager.admin.addres</td><td align='right'>8033</td><td align='right'>0000</td></tr>
	<tr><td>yarn.resourcemanager.webapp.address</td><td align='right'>8088</td><td align='right'>0000</td></tr>
	<tr><td rowspan='3'>NodeManager</td><td>yarn.nodemanager.localizer.address</td><td align='right'>8040</td><td align='right'>8040</td></tr>
	<tr><td>yarn.nodemanager.address</td><td align='right'>8041</td><td align='right'>0000</td></tr>
	<tr><td>yarn.nodemanager.webapp.address</td><td align='right'>8042</td><td align='right'>8042</td></tr>
	<tr><td rowspan='4'>JobHistory</td><td>mapreduce.jobhistory.admin.address</td><td align='right'>10033</td><td align='right'>0000</td></tr>
	<tr><td>mapreduce.jobhistory.address</td><td align='right'>10020</td><td align='right'>0000</td></tr>
	<tr><td>mapreduce.jobhistory.webapp.address</td><td align='right'>19888</td><td align='right'>0000</td></tr>
	<tr><td>mapreduce.jobhistory.webapp.https.address</td><td align='right'>11001</td><td align='right'>0000</td></tr>	
	<tr><td rowspan='3'>OOZIE Service</td><td>OOZIE_ADMIN_PORT</td><td align='right'>11000</td><td align='right'>0000</td></tr>
	<tr><td>OOZIE_HTTP_PORT</td><td align='right'>8031</td><td align='right'>0000</td></tr>
	<tr><td></td><td align='right'>11443</td><td align='right'>0000</td></tr>
	<tr><td>HiveServer2</td><td>hive.server2.thrift.port</td><td align='right'>10000</td><td align='right'>0000</td></tr>
	<tr><td>HiveServer2</td><td></td><td align='right'>9083/td><td align='right'>0000</td></tr>
	<tr><td>Spark Job History</td><td></td><td align='right'>18088</td><td align='right'>0000</td></tr>
</table>

