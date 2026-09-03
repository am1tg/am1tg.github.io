hello!!!<br>
let's do a ctf together<br>

### Level 0:<br>
"we are all starting somewhere"<br>
username: natas0<br>
password: natas0<br>
<img width="1100" height="520" alt="image" src="https://github.com/user-attachments/assets/4094b0c6-e6b8-4373-a82b-62869c28de71" /><br>
let's right click and choose:<br>
<img width="338" height="39" alt="image" src="https://github.com/user-attachments/assets/82878a7c-b71e-4db1-be5a-f40ff08d11b4" /><br>
and BOOM!!!<br>
<img width="1084" height="366" alt="image" src="https://github.com/user-attachments/assets/45b2dc20-7aef-44f1-8182-93f4461c594f" /><br>
We found the password!<br>
### Level 1:<br>
"moving on"<br>
username: natas1<br>
password: scfWG6qNEIdzqVyfRwEGXyNUfFZkZeQ7<br>
<img width="1100" height="520" alt="image" src="https://github.com/user-attachments/assets/a3922bcb-c7be-4818-8b13-f5a74c48baf7" /><br>
looks like we cand right click this time...<br>
but we can press ctrl+U to get to the source page:<br>
<img width="1089" height="389" alt="image" src="https://github.com/user-attachments/assets/e4df494f-f0bf-4e34-a0b3-a5bc4be45947" /><br>
### Level 2:<br>
"This is easy"<br>
username: natas2<br>
password: vsDOxoXyq3wckCP1ZmTZ71ngIA606odB<br>
<img width="1100" height="520" alt="image" src="https://github.com/user-attachments/assets/20b2e262-609c-4f37-b706-0ed8bfc77654" /><br>
We will see about that!<br>
there is actually nothing in the source of the page:<br>
<img width="1075" height="314" alt="image" src="https://github.com/user-attachments/assets/169803fe-15f8-4ba7-8abc-e7218507cdb9" /><br>
except for that pixel.png that reveals a "files" directory that is probably accessible<br>
let's try:<br>
<img width="556" height="330" alt="image" src="https://github.com/user-attachments/assets/5fd47b24-9ce2-416a-bcd9-ade9c91c9c9c" /><br>
nice! what is in this users.txt file?<br>
<img width="365" height="152" alt="image" src="https://github.com/user-attachments/assets/16df0ec1-fb01-43e3-9688-ed1e51d78f22" /><br>
### Level 3:<br>
"To the next level"<br>
username: natas3<br>
password: K30JrSRHzjxq3paUQuwozY4MNvmNFyhI<br>
<img width="1100" height="520" alt="image" src="https://github.com/user-attachments/assets/09025669-e216-40cf-830e-747470089353" /><br>
looks the same...<br>
you know the drill...<br>
<img width="1083" height="314" alt="image" src="https://github.com/user-attachments/assets/04051063-46fc-468d-91d3-1be9e170df2e" /><br>
after researching long and hard about this "not even google will find it this time" i stumbled across this website:<br>
<https://developers.google.com/crawling/docs/robots-txt/create-robots-txt><br>
which says that google has a web crawler that scans sites and sites can config a robots.txt files to control what it accesses<br>
so i tried accessing it myself:<br>
<img width="515" height="121" alt="image" src="https://github.com/user-attachments/assets/e520ab79-46f3-478b-b164-27bad511c81d" /><br>
looks good! let's try this /s3cr3t/ path:<br>
<img width="579" height="311" alt="image" src="https://github.com/user-attachments/assets/5656bb5d-3853-4e4c-b5d4-faa070a60e6e" /><br>
yesss<br>
<img width="589" height="95" alt="image" src="https://github.com/user-attachments/assets/59d18d22-1133-4385-98d7-233e0262ecda" /><br>
### Level 4:<br>
"This is only getting easier"<br>
username: natas4<br>
password: JDrPnuZAKyl6MkiqQGFIddrqpvgOASth<br>
<img width="1100" height="520" alt="image" src="https://github.com/user-attachments/assets/67674bd4-0e54-46f8-923c-c4c08ab0c1b0" /><br>
looks like it is time to open burp suite!<br>
this is what our request looks like:<br>
<img width="1211" height="206" alt="image" src="https://github.com/user-attachments/assets/4b4a3333-037d-4db4-9849-e7c391a79962" /><br>
I believe that if i change this 4 in the referer field to 5 I will be granted access:<br>
<img width="627" height="174" alt="image" src="https://github.com/user-attachments/assets/91c5c2a5-2266-43c9-8089-4f3704e7c812" /><br>
I was right!<br>
### Level 5:<br>
"Give me a real challenge"<br>
username: natas5<br>
password: e4z2Noy3oqwPJUWzJH0dseN67Cn1sy2M<br>
<img width="1100" height="520" alt="image" src="https://github.com/user-attachments/assets/0e59913b-4cf7-44ee-bec2-c2151e06b4d1" /><br>
thankfully I'm already in burp suite lets look at the request:<br>
<img width="1195" height="192" alt="image" src="https://github.com/user-attachments/assets/a6934ae9-15ba-4f7f-9f46-970088395d13" /><br>
This is lying!<br>
let's change it to 1:<br>
<img width="692" height="179" alt="image" src="https://github.com/user-attachments/assets/13e4f2cf-2de5-4339-88db-43d220e91213" /><br>
done!<br>
### Level 6:<br>
"You can't stop me"<br>
username: natas6<br>
password: 7mhjtShJAcld2NYbKHEadnhEwRn2P8VT<br>
<img width="1100" height="520" alt="image" src="https://github.com/user-attachments/assets/710609c2-4b67-466b-937d-113a6841f383" /><br>
lets look an the source code:<br>
<img width="1077" height="576" alt="image" src="https://github.com/user-attachments/assets/e1d5c84c-1245-4a1b-91eb-c0d100a09e3b" /><br>
looks like the $secret must come from -> includes/secret.inc<br>
let's see if we can access this file:<br>
<img width="582" height="125" alt="image" src="https://github.com/user-attachments/assets/34006aad-07d0-4ef4-a363-0f9a0d8c518d" /><br>
yes we can! and we got the secret -> "FOEIUWGHFEEUHOFUOIU"<br>
why don't we submit it:<br>
<img width="646" height="241" alt="image" src="https://github.com/user-attachments/assets/fe1f6c2f-ca59-4a97-88c3-db76d9a2b9fd" /><br>
### Level 7:<br>
"I'm on fire!"<br>
username: natas7<br>
password: B1szg95UcTnrzwnF3i3TzYHlyYh8iBV0<br>
<img width="1100" height="520" alt="image" src="https://github.com/user-attachments/assets/2771c2de-504a-4d8e-a23c-7a8e5eaad439" /><br>
This is new...<br>
look what we got from the source page:<br>
<img width="1094" height="415" alt="image" src="https://github.com/user-attachments/assets/5631dbac-0ea3-47f5-a324-017120e46216" /><br>
The hint says that the password is in this file path -> /etc/natas_webpass/natas8<br>
and looks like this hrefs gives a variable "page" to the "index.php" page to return an html file:<br>
what would happen if we give "/etc/natas_webpass/natas8" as the path we what "index.php" to return?<br>
<img width="1100" height="255" alt="image" src="https://github.com/user-attachments/assets/27bb1d4f-1cbf-4172-a933-306feb28d249" /><br>
We would get the password for natas8!<br>
### Level 8:<br>
"To infinity and beyond!"<br>
username: natas8<br>
password: ugXL95KQmUAJJj6bMezOlBNDyI9Imwkc<br>
<img width="1100" height="520" alt="image" src="https://github.com/user-attachments/assets/a18a80c1-18e4-4943-927c-b4f66112daed" /><br>
another secret...<br>
source code:<br>
<img width="1082" height="622" alt="image" src="https://github.com/user-attachments/assets/483e0042-a412-4630-bc44-45019957ca8d" /><br>
we can see the encoded secret and we can see the encoding function, let's reveres this so we decode the $encodedSecret to get the plain text secret:<br>
so the regular function is doing: base64 -> reveres str -> binary to hex<br>
we need to do the opposite so: from binary to hex -> reveres str -> from base64<br>
This is the recipe and the output:<br>
<img width="1106" height="592" alt="image" src="https://github.com/user-attachments/assets/eddc93a6-fa99-4930-9fea-f37702737a89" /><br>
when we submit it ("oubWYf2kBq"):<br>
<img width="621" height="225" alt="image" src="https://github.com/user-attachments/assets/5d2082b8-bf82-4746-bb1a-2c47fe977aa8" /><br>
We get the next password!!!<br>
### Level 9:<br>
"Never say never"<br>
username: natas9<br>
password: UdxmI27dTaXmnd1rxKQTfws6jihTdcQ9<br>
<img width="1100" height="520" alt="image" src="https://github.com/user-attachments/assets/cc1ba990-e6e0-480e-81d5-b96433a1dca8" />
source code:
<img width="1062" height="583" alt="image" src="https://github.com/user-attachments/assets/8191838d-b72d-4d69-87c0-bce152285001" />
this is probably the most vulnerable code possible:
to prove it I have entered the input:
<img width="432" height="56" alt="image" src="https://github.com/user-attachments/assets/598466ef-3d74-462e-a65b-2652e53e2f70" />
and got:
<img width="544" height="735" alt="image" src="https://github.com/user-attachments/assets/d6bd02f6-0416-4c3e-a345-9faba2b6369e" />






