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

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/b252e0bb-262e-4163-bf96-02e7224bb25e"/>
</p>
<p>
Go to the Networking section and make sure the Virtual Network, Subnet, and Public IP says new. Once that is done go to the bottom left and click review and create.
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/f49daf98-f266-4215-94c0-a6e3b2cd46cb"/>
</p>
<p>
Once the validation passed is done you can click the create button in the bottom left. 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/5fe32d8e-8983-4864-bb05-12342eea7d1a"/>
</p>
<p>
Then once the deployment is done you will see the green check on the left side.
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/5925af95-ec52-441c-b073-711eb4b0131c"/>
</p>
<p>
Next type Virtual Machine in the search bar and you will see that VM1 has been created
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/e455dae0-0bea-4a61-a47f-f53de0340a6a"/>
</p>
<p>
Click the create button and go to Azure Virtual Machine
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/342ad900-a647-440b-8af2-33c835cb8218"/>
</p>
<p>
Under Resource Group type rg-01, under region click US West US 3, under Image click Ubuntu Server x64, and the size under Standard Ec2 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/13d30976-2eca-437d-9e27-b77a5f152e59"/>
</p>
<p>
In Authentication type click password, username we will put labuser, and the password can be the same as VM1
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/d20c370f-92e3-4999-ae1d-a018db07517c"/>
</p>
<p>
Go to the Network section and make sure virtual network says -vnet, subnet says default (XXXX), and the Public IP needs to say new
</p>
<br />


<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/d83ca62b-0f02-42c8-9f26-90b158323646"/>
</p>
<p>
Go to the Review and Create tab and let the Validation passed.
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/97bb4626-02ce-48b9-b391-59ef3b23e13f"/>
</p>
<p>
Next the deployment commence its progess
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/2d646e28-fd87-4c87-a38a-0741168be378"/>
</p>
<p>
Next the deployment will finish the progess
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/12aaa2f7-2ef5-4eac-9172-e36f81d264a4"/>
</p>
<p>
Type Vritual Machine in the search bar, and you will see VM1 and VM2.
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/2ea080a7-0694-4ef1-a24e-dfeea8ca4af7"/>
</p>
<p>
Click on VM1 and copy the public IP
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/c106b2a5-62f7-4a33-9ae2-508163e42aa0"/>
</p>
<p>
Go to your search bar and type Remote Desktop Connection
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/30347048-54d0-41bb-b138-28afd05eaf38"/>
</p>
<p>
Next paste the IP address in the computer section and click connect
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/e977dbab-0dd1-463c-af65-e31fbb8c848f"/>
</p>
<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/bb1a574e-62fe-405e-9865-af299935df37"/>
</p>
<p>
In the username section type labuser then in the password section type the password you created for VM1
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/b42fa5f1-9ca4-4179-b82a-bece3a1339c7"/>
</p>
<p>
Next the identity tab should open, click yes to let the VM load
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/e9ab0823-f7d4-4770-9ef4-7575888c8ad8"/>
</p>
<p>
Once the VM loads click no for the following in the iamge above
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/e2e59220-569f-4713-a085-9fd3ad929575"/>
</p>
<p>
A Network tab should open click yes 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/ccb38d24-b47c-4d88-9ef8-564a9b75f0a7"/>
</p>
<p>
Open microsoft excel and click start without your data
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/6d0fbfcf-090d-4407-a52d-10a48218677c"/>
</p>
<p>
Next click continue without this data
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/5211cfd5-2ca7-40db-8911-ae403adb65fc"/>
</p>
<p>
Next click confirm and continue
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/ca7fc9cf-d18f-40ed-a40b-4a06dfcf05c4"/>
</p>
<p>
Next to finish click confirm and start browsing 
</p>
<br />
