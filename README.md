<h1> Manage Websites With Apache2</h1>
<h2>Description</h2>
<p>In this lab, I will get familiar with Apache2 by configuring it on a Linux machine and learn to enable and disable websites in Apache2. </p>
<br />
<br />
<h2>Utilities Used</h2>
<ul>
    <li><b>Ubuntu</b> -Operating system used for the configuration</li>
    <li><b>Apache2</b> -Web server software for hosting websites</li>
</ul>
<br />
<h3>Task 1: Install Apache</h3>
<p align="center">
<img src="https://i.imgur.com/puRfMrt.png" height="80%" width="80%" alt="pre debug"/>
</p>
<p align="left"> First thing I did was update the current programs, to avoid configuration errors. I then installed Apache2 and started the program.</p>
<br />
<p align="center">
<img src="https://i.imgur.com/ZS50vqQ.png" height="80%" width="80%" alt="nano"/>
</p>
<br />
<br />
<h3>Task 2: Configuring sites</h3>  
<br /> 
<p align="center">
<img src="https://i.imgur.com/XzESrPd.png" height="80%" width="80%" alt="max"/>
</p>
<p align="left"> First I moved our company website with the 'sudo mv /opt/devel/ourcompany /var/www/ourcompany' command. I then change the directory where the files are stored. Instead of /var/www/html we will put our site in /var/www/ourcompany, seen above in the config file.</p> 
<br /> 
<p align="center">
<img src="https://i.imgur.com/BWbW8u5.png" height="80%" width="80%" alt="calc"/>
</p>
<p align="left"> I then enable the configuration file and reload the program to have Apache2 reread the config updates.</p>
<br /> 
<br />
<h3>Task 3: Additional configurations</h3>
<p align="center">
<img src="https://i.imgur.com/Ljn5Qyb.png" height="80%" width="80%" alt="calc"/>
</p>
<p align="left"> I can see the footer isn't showing anything. Enabling the include mod allows Apache2 to process Server Side Includes, which is used to display the footer. I enable the include mod and restart Apache2 to run the updates. </p> 
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/vOxn20S.png" height="80%" width="80%" alt="calc"/>
</p>
<p align="left"> Last thing I do is edit the config file once more to run Server Side Includes, to display the footer. Lastly, I reload Apache2 to enable the updates and visit the website to make sure everything is working properly.</p> 
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/ntpoW7d.png" height="80%" width="80%" alt="calc"/>
</p>
<h3>Conclusion:</h3>
<p> This was pretty straight forward. I can see why Apache2 is used to host sites. Writing the code to develope the website is a whole other story.</p> 
