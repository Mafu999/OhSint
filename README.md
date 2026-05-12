<h1 align="center">Ohsint</h1>
<div align="center">

  <img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/29d6477d-e314-4d5f-94ba-0f063b6a3cd5" />

  This is my Osint's lab where I find information about an user based on an image he posted online. This lab is consisted of a few questions about this user and I have to answer it
  using Open Source resources to find information and describe each step that I took to find it.

  <h2>What information can you possibly get with just one image file?</h2>
  <img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/96818f91-f6f1-4f10-82f6-cebb789bc8a1" />
  
  This image seems to be just a simple Windows XP Wallpaper that you used to see when you were younger, but it is impressive how much information ou can extract from it.

  <h3>What is this user's avatar of?</h3>
  
  To find this information, we have to extract some information from the image in order to see if we can get useful information. To do this, I used a tool called <i>Exiftool</i> you can find it online but I'd rather download this tool in my pc by <a href="https://chocolatey.org/">Chocolatey</a>. If you have Chocolatey in your pc, you can easily install by typing this command on your shell <code>choco install exiftool --version=12.40</code>
  Once I installed, I've opened shell in the directory where the image was and executed the command: <code>exiftool .\imagename.jpg</code> and it returned these informations: 

  
  <img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/0c78d8d3-0615-4b60-81cd-26982838084b" />

  Here we saw some metadata extracted from the image, and the copyright is in name of <i>OWoodflint</i>. So, let's search it in some search engine of your preference.

  <img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/ecf5417f-2a96-4f78-a44d-df6864ac97eb" />

  We found in this search the only social media related to this username that is X, and the profile image is a cat, so I assume that this is the user's avatar, a cute little <b>cat</b>.

  <h3>What city is this person in?</h3>
  We found the user's X account and a personal blog, let's dive in to see more.

  <img width="600" height="200" alt="image" src="https://github.com/user-attachments/assets/2bd6a221-6e0c-4783-8e4e-78e494256f6d" />

  I found a post on is X account saying that he uses free wifi, and he shares the bssid. Let's go to wigle.net and search his bssid.

  <img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/a331c1b2-e1d5-4c8d-909e-a34c3212ac10" />

  We found the location of the router he uses his free wifi, and it is in London, so he lives there. The SSID is "Unilever Wifi".

</div>


