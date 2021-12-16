# Nexus Apache Starter Kit

Nexus is a peer-to-peer Micro Social Network.  
This is the Nexus Apache Starter Kit repository.  

## Requirements

An Apache server.  
If you have a website hosted on a shared web host plan, most chances are this is the case.

## Getting started

Download the `nexus/` folder and its content, or the `nexus.zip` archive and unzip it.  
Upload the folder and files on your web server.  

 - You can use an FTP file manager like FileZilla.  
 - Many web hosts also offer a web-based FTP file manager.  
 - If you have a CMS installed, you may also be able to use its backend.  

> Make sure the `.htaccess` file has been properly uploaded, otherwise other Nexus instances will not be able to connect to yours.

Upload your media files in `nexus/media/` if any.  

Launch the Editor: `http://your-website.xyz/nexus/?edit` and fill in the form.  
Click `⇣` to download your new .json file.  
On your web server, replace `nexus/source/nexus.json` with your updated Nexus .json file.  

Access your Nexus: `http://your-website.xyz/nexus`.
 
More detailed documentation is available here: [nexus-dock.github.io](https://nexus-dock.github.io/)   

## Other resources
   
Nexus Code repository: [I-is-as-I-does/Nexus](https://github.com/I-is-as-I-does/Nexus)  
GitHub Pages Starter Kit: [I-is-as-I-does/Nexus-Github-starter](https://github.com/I-is-as-I-does/Nexus-Github-starter)
