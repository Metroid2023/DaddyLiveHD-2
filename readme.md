<b>FIXED WORKING Reinstall on huggingface or local</b> to get it working.<br>
EXAMPLE URLS<br>
https://your.hugging.hf.space/playlist/channels<br>
https://your.hugging.hf.space/playlist/events - Events wont update<br>
OR<br>
https://your.hugging.hf.space/proxy?url=https://new.newkso.ru/ddy6/***/mono.m3u8<br>
See the list.of.direct.urls.txt or json file for the direct stream urls<br><br>

<b>DaddyLive Proxy Server (Formally Pigzillaaaaa)<br>
Usual upload to hugging face etc</b><br>

<b>HuggingFace Setup</b><br>
1, Download the docker file <a href="https://github.com/MarkMCFC/tfms.xyz/blob/main/Dockerfile">Dockerfile</a><br>
2, Now sign up for a FREE ACCOUNT - https://huggingface.co - This is going to host your proxy<br>
3, On HuggingFace look to the top‑rightish corner & click 'Spaces' Then Click 'New Space'<br>
4, Name: Enter any name you want<br>
5, Select the Space SDK: Choose 'Docker'<br>
6, Visibility: Select/Leave Public<br>
7, Click Create Space<br>
8, Click The Files Tab Then click 'Contribute' now click 'Upload Files' & upload the 'Docker file' from 'Part 1' (Drag & Drop)<br>
9, Now Click 'Commit New File To Main' (Its at the bottom) & WAIT.... for the build to say 'RUNNING'<br>
10, Click the '3 Dots' next to settings<br>
11, Choose 'Embed this Space'. It will show you the url of the space. Your own proxy url, Copy The Url & Keep Safe<br><br>
===========================================================================<br>
<b><h2>Quick Setup on huggyface Sign-In to huggy First</h2></b>Just duplicate this space<br>
The easiest way to get pigzilla/daddylive 'Proxy'<br>
See the huggingface url below Click the 3 dots (top right) & select 'Duplicate this space' Give it a 'Name' & Change it from 'Private to Public'<br>
https://huggingface.co/spaces/dadproxy-tfms-xyz/tfms-xyz-newworkingdad/<br><br>
Example Urls<br>
https://your.hugging.hf.space/playlist/channels<br>
https://your.hugging.hf.space/playlist/events<br><br>

<b>The below playlist/streams can still be used but you are best off using the urls above</b><br>
https://dadurls.netlify.app/<br><br>
Here is the daddy events list (you probably dont need this as it does not update but some have asked for it)<br>
https://pigdadevents-tfms-xyz.netlify.app/<br><br>
If you already have a huggingface account pointing to pigzillaaaa daddylive streams then you already have the proxy<br>
https://your.hugging.hf.space/<br><br>
===========================================================================<br><be>
## docker-compose
1. Clone the repository
   ```bash
   git clone https://github.com/Metroid2023/DaddyLiveHD-2
   cd DaddyLiveHD-2
   ```
2. Launch the service:
   ```bash
   docker-compose up -d --build
   ```
3. Visit the proxy at:
   ```text
   http://localhost:7861  
4. Channels playlist is accessible via: **http://localhost:7861/playlist/channels**. (Refresh playlist from your iptv player to update)</br>
   Events playlist is accessible via: **http://localhost:7861/playlist/events**. (Refresh playlist from your iptv player to update)
5. Enjoy!

<b><u>Self Hosting Tested & Working on Ubuntu20</u></b><br>Note: The playlists do not download when your are self hosting you will need to use the urls from the quick setup guide (dadurls.netlify.app)<br>

1, Clone the repo:<br>
git clone https://github.com/Metroid2023/DaddyLiveHD-2<br>

2, SSH into the daddy folder (which is called DaddyLiveHD-2):<br>
cd tfms.xyz<br>

3, Launch the service:<br>
docker-compose up -d --build<br>

Visit the proxy at<br>
http://localhost:7861<br>
http://localhost:7861/proxy?url=https://new.newkso.ru/ddy6/***/mono.m3u8<br>
You can also use the urls from the quick setup guide above<br><br>
If You Need To Install Docker On Ubuntu:<br>
snap install docker<br><br>
<b>Full credit must go to:</b> <b><u>Pigzillaaaaa</u></b><br><br>
See Forum, Join Up! Plenty of goodies will be offered - https://forum.tfms.xyz<br>
Join our discord: https://discord.gg/F3MzfJAffG (#iptv)<br><br>

===========================================================================<br>
<h2>Vercel</h2>
1. Sign up to https://vercel.com/signup and select Hobby then click **Deploy** button. <br><br>
<a href="https://vercel.com/new/clone?repository-url=https://github.com/MarkMCFC/tfms.xyz" target="_blank"><img src="https://vercel.com/button" alt="Deploy with Vercel"/></a>
<br><br>
2, Connect your github account to vercel, set the scope and set the repository name (eg. dproxy) then click Create<br>
3, Wait for the project to build. If you see a ":)" then you are good to go.<br>
4, Go to the dashboard and under Domain, copy the url (eg. https://dproxy-g327.vercel.app).<br>
5, Channels playlist is accessible via: https://dproxy-g327.vercel.app/playlist/channels. (Refresh playlist from your iptv player to update)<br>
6, Events playlist is accessible via: https://dproxy-g327.vercel.app/playlist/events. (Refresh playlist from your iptv player to update)<br><br>
Optional: Change the timeout(Function Max Duration) and location(Function Region) in Settings->Functions
