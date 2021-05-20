# Sniffe-The-Ntework-Package-Sniffer-.github.io
<!DOCTYPE html>
<html>
<head>
	<meta http-equiv="Content-Type" content="text/html"; charset="utf-8"/>
	<title>Sniffe</title>
</head>

<body>
<table width="100%" height="60" border="0%" cellspacing="5" cellpadding="5" bgcolor="#000000">	
	<tr>
		
		<td align="left">
	
	
			<table width="100%"  border="0%" align="centre" cellspacing="3" cellpadding="3" >	
	
			<td width="80"><font face="Verdana, Geneva, sana-serif" color="White"><h2>  &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp  &nbsp  &nbsp  &nbsp  &nbsp  &nbsp  &nbsp  &nbsp  &nbsp  &nbsp  &nbsp  &nbsp  &nbsp  &nbsp SNIFFE....The Network Packet Sniffer</h2></font></td>
	
		
	
	
	
			</table>
		</td>
	
	</tr>
</table>
	
	<p>

		&nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp  &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp <img src="snifff.jpg" width="300" height="300" align="center">
    </p>
		
	<table width="100%" height="85" border="0" cellspacing="5" cellpadding="5" bgcolor="#000000">
		<tr>
			<td width="338" align="centre"><font face="Verdana,Geneva, sans-sarif" color="white" size="5"> &nbsp  &nbsp  &nbsp  &nbsp  &nbsp  &nbsp  &nbsp  &nbsp  &nbsp  &nbsp  &nbsp  &nbsp  &nbsp  &nbsp  &nbsp  &nbsp  &nbsp  &nbsp  &nbsp  &nbsp &nbsp  &nbsp  &nbsp &nbsp  &nbsp  &nbsp  &nbsp  &nbsp  &nbsp <strong>Version 1.0</strong>
			</td>
		</tr>
	</table>	
		
		
		
		
		
		
	<p>
		<table  width="100%" height="300" border="0%" cellspacing="0" cellpadding="0">
		<tr>
			<td> <h3>TABLE OF CONTENT</h3>
					<ul>
						<li>Introduction</li>
						<li>Network Sniffing</li>
						<li>Benefits</li>
						<li>Types of packet sniffing</li>
						<li>Sniffing through a hub in passive sniffing</li>
						<li>Sniffing through a hub in active sniffing</li>
						<li>Software requirement specification</li>
						<li>What is Jpcap</li>
						<li>Software process model</li>
						<li>Limitations</li>
					</ul>
			</td>
		
		
			<td background="cyber4.jpg" width="70%" height="100" border="1" align="centre">
		    </td>
			
		</tr>
		
 		</table>
	</p>	
	<p></p>
	<p>
		<u><strong><h3>Introduction</h3></strong></u>
			<ul>
				<li>Packet sniffing is a process of monitoring & capturing all data packets passing through a software, hardware device or network; i.e., it is a technique in which a user sniffs data belonging to other users of the network</li>
				<li>Packet sniffers can operate as an administrative tool or for malicious purposes</li>
				<li>They are programs used to read packets that travel across the network layer of the Transmission Control Protocol/Internet Protocol (TCP/IP) layer.</li>
			</ul>
			<p>
		&nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp <img src="Picture1.jpg" width="500" height="300" align="center">
		</img>
		</p>
	</p>
	<p>
		<u><strong><h3>Network Sniffing</h3></strong></u>
		<p>
		&nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp <img src="Picture2.jpg" width="50%" height="300" align="centre"></img>
    </p>		
			
	<p>
		<ul>
			<li>Traffic analysis</li>
			<li>Detecting root cause of a network issue</li>
			<li>Network security & compliance</li>
			<li>Troubleshooting Network Issues</li>
			<li>Bandwidth Management</li>
			</ul>
	</p>		
	<p>
		<u><strong><h3>Types of Packet Sniffing</h3></strong></u>
		<p>There are two main types of packet sniffers:</p>
		<ol>
			<li><h4>Hardware Packet Sniffer:</h4></li>
			It is clear from the name itself that, it is designed to be plugged into a network and to examine it. It is particularly useful when attempting to see traffic segment of a specific network.
			
	        <li><h4>Software Packet Sniffer:</h4></li>
			A software packet sniffer changes the configuration so that the network interface passes all the network traffic up the stack. This configuration is called promiscuous mode for most network adapters. 
		</ol>	 
	</p>
	
	<p>
		&nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp <img src="Picture4.jpg" width="50%" height="300" border="1" align="centre"></img>
	</p>
	
	<p>
		<em><h4>Sniffing through hub i.e. is passive sniffing:-</h4></em>
		 &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp <img src="Picture5.jpg" width="50%" height="300" align="centre"></img>
	</p>
			
	<p>
		
       <em><h4>Sniffing through switch i.e. is active sniffing:-</h4></em>
		&nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp <img src="Picture6.jpg" width="50%" height="300" border="1" align="centre"></img>
			
    </p>
	
	
	<p>
		<u><strong><h3>Software requirment specification:</h3></strong></u>
		<p>
			<em><h4>External Interface Requirements:<h4></em>
			<ul>
			<u><strong>User Interfaces</strong></u>
			</ul>
			<ul>
			<li>Help and Tooltips are available for easy understanding.</li>
			<li>Graphical interface is available for ease and convenience of the user.</li>
			<li>Most functions require mouse click thus simplifying operations.</li>
			<li>Tools strip menu is available for faster access of menus.</li>
			<li>Shortcut keys are available for experienced users.</li>		
            </ul>
			
			<p> 
			<u><strong>&nbsp &nbsp Hardware Interfaces</strong></u>
			<ul>
			<li>Network interface card is required for packet capture</li>
			<li>1.5 MB of hard disk space.</li>
			<li>1 GB RAM (Random Access Memory).</li>
			</p>
            <p>
			<u><strong>Software Interfaces</strong></u>
			<p>
			This software requires following software interfaces:
			</p>
			<ul>
			<li>Jpcap</li>								
			<li>WinPcap V4.0.1</li>			
			<li>SharpPcap V1.5</li> 
            </p>
		</p>
</p>	
	
<p>
<h3><u font face="Verdana, Geneva, sana-serif" color="blue"><strong> What is Jpcap:-</strong></u></h3>
	<table width="50%" height="60" border="1%" cellspacing="5" cellpadding="5" font face="Verdana, Geneva, sana-serif" color="White">
		<tr>
			<td>Jpcap is an open source network packet capture library based on the libpcap and winpcap libraries that you can use with Java to capture and display network traffic on linux, windows and mac. Jpcap captures Ethernet, TCP, UDP, IPv4, IPv6 etc packets and analyzes each packet’s header and data payload.</td>
		</tr>
	</table>	
</p>

	<p>
	<ul>
		<u><strong><h3>Software process model:</h3></strong></u>
		<p>
		&nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp <img src="Picture7.jpg" width="50%" height="300" align="centre"></img>
    </p>	
	</ul>
	</p>	
	
<p>	
	<u><strong><h3>Limitations:</h3></strong></u>
	<p>
	<ul>
	<li>Your system administrator might not allow the use of packet capture software due to security concerns with intercepting traffic.</li>
	<li>On non-Windows systems, root permissions are required to access the network port in promiscuous mode, and thus to run packet capture.</li>
	</li>You can record only those messages that are sent from, or received by, the system running Rational Integration Tester. You cannot record messages between remote systems.</li>
	</ul>
	</p>


</p>
	
</body

</htmll>
