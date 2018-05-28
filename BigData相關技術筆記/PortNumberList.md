### Hadoop 2.7.2/3.0.0 環境用到的Port Number List:

<table>
   <tr>
      <td>Service</td>
	  <td>Parameter</td>
      <td>Hadoop 2.7.2 Port</td>      
	  <td>Hadoop 3.0.0 Port</td>
   </tr>
	<tr><td rowspan='4'>NameNode</td><td>fs.defaultFS</td><td>8020</td><td>8020</td></tr>	
	<tr><td>dfs.namenode.http-address</td><td>50070</td><td>9870</td></tr>
	<tr><td>dfs.namenode.https-address</td><td>50470</td><td>9871</td></tr> 
	<tr><td rowspan='5'>NodeManager</td><td>yarn.nodemanager.address</td><td>${yarn.nodemanager.hostname}:0</td><td>${yarn.nodemanager.hostname}:0</td></tr>
	<tr><td>yarn.nodemanager.localizer.address</td><td>${yarn.nodemanager.hostname}:8040</td><td>${yarn.nodemanager.hostname}:8040</td></tr>
	<tr><td>yarn.nodemanager.webapp.address</td><td>${yarn.nodemanager.hostname}:8042</td><td>${yarn.nodemanager.hostname}:8042</td></tr>
	<tr><td>yarn.nodemanager.collector-service.address</td><td>${yarn.nodemanager.hostname}:8048</td><td>${yarn.nodemanager.hostname}:8048</td></tr>
</table>

