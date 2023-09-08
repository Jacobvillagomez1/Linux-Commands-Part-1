# Linux-Commands-Part-1
<p align="center">
<img src="https://wallpapers.com/images/featured-full/linux-adreajudr0n7ad5a.jpg"/>
</p>
<p align="center">
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/4e436e5f-a61b-482f-8332-27b7f6407bee"/>
</p>
<h1>Linux Virtual Machine Installation Configuration Commands</h1>
This tutorial outlines the installation of a virtual machine running linux, then using commands in linux.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: Linux Commands Part1](https://youtu.be/RKCSIhXRWmc)

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

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/24780257-fbeb-44d0-87f8-e137e94ba735"/>
</p>
<p>
Next open a new tab and type MobaXterm download in the search bar. Then click the Download button 
</p>
<br />


<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/0d1acb44-8d52-49e3-9c63-d6b050d01c01"/>
</p>
<p>
Go to the Home Edition and click Download Now
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/931ef7bd-3a11-4d20-b492-447325f6c797"/>
</p>
<p>
Next click the MobaXterm home Edition and the current version
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/da66a4a4-5587-475f-8427-eb46500aa735"/>
</p>
<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/045b62d1-d6b8-4493-a1b1-d66dc9e5a6b3"/>
</p>
<p>
Type File Explorer in the search bar in the VM and go to your downloads section. Click the MobaXterm file and Extract All. Then Click Extract
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/c552afbc-ef7d-4af9-b6bb-43ff9c4bec37"/>
</p>
<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/74c5df0f-b10d-41c1-ad5d-334408a381f8"/>
</p>
<p>
Once the extraction is done, double click MobaXterm app, you will see the app load 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/abcd626e-fc70-47e9-84b3-a2f6af246a72"/>
</p>
<p>
Once the software loads you can click the light or dark mode, I'm going to click the dark mode so its easier to see on the screen. Also click Start local terminal
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/aac29b3c-5dd8-4a2c-b74f-c67b0f4328ea"/>
</p>
<p>
Click allow access to let the software load
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/72fcb33c-470a-43fc-a564-7e12e3d3a6db"/>
</p>
<p>
Next go back to Microsoft Azure and copy the public IP of VM2, we are going to log into VM2 through VM1 using MobaXterm
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/a4f9d271-3568-41ce-8300-d04860513998"/>
</p>
<p>
Next type ssh labuser@ public IP of VM2. So to explain this we are using ssh (Secure Shell) to tap into VM2 through VM1. We then type the username of VM2 for this case its called labuser then use the @ symbol which the followwing public ip address of VM2 typed after.
</p>

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/67a15238-533f-46cc-a173-2c432bf44fd3"/>
</p>
<p>
Once that is done, type your password in and it will not show you just have faith you are typing the password correctly. Then you can click no to save the password
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/5168d8e1-bafe-4a5f-bbcc-fd0057c5e008"/>
</p>
<p>
Next you will know you are logged in with the name labuser@VM2 show like the image above
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/8cbe711f-776a-4c40-a8be-c948d5134572"/>
</p>
<p>
Next type ls in the command line this will list all the files out for this we will have none in the VM. Then you can type pwd for print working directory this will show you the directory 
</p>
<br />
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/86b2f344-4b0e-49f9-b7d2-abdb4ad70cbc"/>
</p>
<p>
Next type ls -l this will list the total number of files in the directory. You can also type ls -al this will list all the files including the hidden stuff, The hidden files will be in blue
</p>
<br />
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/49ccefc8-d581-4c2b-8b57-43c09933292b"/>
</p>
<p>
We can next type cd / this puts us in the cd file, next we can type cd/usr/bin this puts us in the user bin file in the directory
</p>
<br />
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/7e88cdba-36ce-4ad0-9668-ea1294086f16"/>
</p>
<p>
Next type cd .. this will put us one file back and then cd {space} will take us out of the file completely 
</p>
<br />
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/a1e6dd3a-213c-4a0a-ba1b-eb94a839a244"/>
</p>
<p>
Next to create a txt file use touch. We can make a blank txt file by typing touch blank.txt and then touch hi.txt
</p>
<br />
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/7f195c9f-b1b2-424d-9071-ab5bd8bbe09c"/>
</p>
<p>
Next to if we type ls again in the command line this time it will list the txt files we just created
</p>
<br />
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/ef7b3146-9d3e-45c7-8cfe-48eeaa9db59b"/>
</p>
<p>
We can also create multiple text file by tpying touch {and then any words after} for this example type touch every word space out like this. Then type ls again and you will see the words layed out in the directory
</p>
<br />
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/09a01976-966c-4317-a58d-944ca850aa91"/>
</p>
<p>
Now to create a txt file in the future type touch -d tomorrow go.txt. To break this down -d is setting the time and then after -d you time how long is is from the current date. For this example we will type tomorrow, then the following txt file we want to create
</p>
<br />


<p>
<img src="https://github.com/Jacobvillagomez1/Linux-Commands-Part-1/assets/143027686/bbacb854-f071-49b6-8139-8cc4a45e8c91"/>
</p>
<p>
Now type ls -l and you will see the go.txt file and the date its set to. Also to exit the directory of VM2 type exit
</p>
<br />
<br />
