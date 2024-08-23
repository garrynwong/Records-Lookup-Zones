<h1>Records & Lookup Zones</h1>

<h2>Description</h2>
Project consists of setting up A and CNAME records in a forward lookup zone.
<br />


<h2>Languages and Utilities Used</h2>

- <b>DNS Manager</b> 

<h2>Environments Used </h2>

- <b>Windows Server 2022</b>

<h2>Program walk-through:</h2>

<h3>Step 1:  </h3>
<p> using DNS manager, create a new A record host name in the forward lookup zone for the DC; enter the name and its mapped ip address; ping created host name from another domain device to verify DNS record and resolution </p>

![1](https://github.com/user-attachments/assets/0083ac8d-3785-484d-af29-9923597bf4ff)


![2](https://github.com/user-attachments/assets/06651fea-d7a5-4469-a480-58cff206b8a4)


![3](https://github.com/user-attachments/assets/d49e272d-f713-4a3b-9af9-a9c55e311e0c)


![4](https://github.com/user-attachments/assets/b7b72d2b-dbd3-453d-9024-270717915416)



____


<h3>Step 2: </h3>
<p>change the ip address of the A record from the previous step to a different ip address; clear the dns cache on the machine with ipconfig /flushdns (this requires elevated permissions such as a domain admin account); ping to verify DNS settings </p>


![5](https://github.com/user-attachments/assets/846f8d36-3d6d-4392-a99c-93f8d151f72b)



![6](https://github.com/user-attachments/assets/a60dde1d-6bb8-413a-b813-940e0f790b1c)







____


<h3>Step 3:  </h3>
<p>create a new CNAME record that points an alias name to a desired domain name; ping the alias name to verify DNS settings</p>


![7](https://github.com/user-attachments/assets/3a20d0ef-e119-4e8d-a5cc-c976167589d8)



![8](https://github.com/user-attachments/assets/a12dff20-f03b-4532-818b-870348bff3bf)



![9](https://github.com/user-attachments/assets/b6c2e5d2-ca90-47de-8885-4307034cb1b0)


____






<h2> Final Thoughts </h2>

<p> In closing, the "DNS Records & Lookup Zones" project streamlines our  .</p>
