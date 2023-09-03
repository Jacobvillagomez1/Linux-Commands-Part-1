# Linux-Commands-Part-1
<p align="center">
<img src="https://wallpapers.com/images/featured-full/linux-adreajudr0n7ad5a.jpg"/>
</p>

<h1>Linux Virtual Machine Installation Configuration Commands</h1>
This tutorial outlines the installation of a virtual machine running linux, then using commands in linux.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Linux
- MobaXterm

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
- Ubuntu </b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Create Resource Group for Virtual Machines
- Create Virtual Machine in Windows
- Create Virtual Machine in Ubuntu
- Log into VM in Windows through Remote Destop Connection  
- Download MobaXterm
- Log into VM Ubuntu in MobaXterm
- Linux Commands in MobaXterm

<h2>Configuration Steps</h2>

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/5cc90908-9713-4ed1-ad9a-dcbe329cf3d6"/>
</p>
<p>
First go to Microsoft Azure Portal and type Resource Group in the search bar.
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/e4838746-a16c-46f5-8616-bad1ed73b033"/>
</p>
<p>
Next for the name type rg-01 and the region under US West US 3
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/264d8682-7477-4dac-a9d4-3d05169cb0c9"/>
</p>
<p>
We can see the Validation passed with the green check above.
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/24cfdc99-2638-4508-a263-42243f013411"/>
</p>
<p>
Now type Virtual Machine in the search bar and create a new Virtual Machine.
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/edd9813a-2757-4ac9-a731-a46b1e29844e"/>
</p>
<p>
For the Resource Group click the one we created rg-01, for the name we can put VM1, and the region under US West US 3. The Image needs to be under Windows 10 Pro x64 Gen2
</p>
<br />


<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/67fd0d80-40bf-4f61-ac80-f9def2a94b03"/>
</p>
<p>
Now under Size needs to be Standard E2, Username for this example wil be called labuser, the Password needs to be long and unique. Once you are done check the Licensing box in the bottom left. (Note) you can write all the info down on a physical paper or you can open up a notepad :).
</p>
<br />
