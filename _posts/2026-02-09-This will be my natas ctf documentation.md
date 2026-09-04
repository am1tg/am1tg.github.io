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
<img width="1100" height="520" alt="image" src="https://github.com/user-attachments/assets/cc1ba990-e6e0-480e-81d5-b96433a1dca8" /><br>
source code:<br>
<img width="1062" height="583" alt="image" src="https://github.com/user-attachments/assets/8191838d-b72d-4d69-87c0-bce152285001" /><br>
this is probably the most vulnerable code possible:<br>
to prove it I have entered the input:<br>
<img width="432" height="56" alt="image" src="https://github.com/user-attachments/assets/598466ef-3d74-462e-a65b-2652e53e2f70" /><br>
and got:<br>
<img width="544" height="735" alt="image" src="https://github.com/user-attachments/assets/d6bd02f6-0416-4c3e-a345-9faba2b6369e" /><br>
but I will play their game and use the grep command given to me:<br>
I will submit this string -> "-r -E '\b[0-9a-zA-Z]{32}\b' * /etc ;"<br>
this will look for any sting that contains letters and numbers in the length of 32 (like the other passwords)<br>
in the etc directory (because this was where the password was in level 7 and i didn't want to search every file on the server even though i could)<br>
this is the output:<br>
<img width="828" height="599" alt="image" src="https://github.com/user-attachments/assets/ccdd8331-52c9-4089-a180-8c24c737560a" /><br>
we got the password for natas10<br>
### Level 10:<br>
"Smells like teen spirit"<br>
username: natas10<br>
password: EgjlkzB6E8LJyf2Obt4q7q4ewt5ZWSNv<br>
<img width="1100" height="520" alt="image" src="https://github.com/user-attachments/assets/f2e0e104-d005-4338-899f-1a6be21ac7f1" /><br>
let's hope it is more secure this time...<br>
<img width="1070" height="669" alt="image" src="https://github.com/user-attachments/assets/57a7dbd3-fa78-4e69-9d78-dc8acf2d3b4b" /><br>
ok looks like we need to get rid of the ";" from the last injection:<br>
but it still works:<br>
<img width="860" height="627" alt="image" src="https://github.com/user-attachments/assets/77830001-a4db-480c-8384-9620e14676b9" /><br>
maybe we were over qualified for the last level ¯\\_(ツ)_/¯<br>
### Level 11:<br>
"Welcome to the jungle"<br>
username: natas11<br>
password: VUMQDmuITOEHzhviLE5V0VG9cPMQkyxd<br>
<img width="1100" height="520" alt="image" src="https://github.com/user-attachments/assets/1edf62af-5acb-47d5-b786-b481420903d2" /><br>
looks like we can change the background color <br>
<img width="727" height="290" alt="image" src="https://github.com/user-attachments/assets/ac9d0601-ee21-4e42-9d95-3ba9db8d330e" /><br>
we do!<br>
source code:<br>
<img width="1026" height="901" alt="image" src="https://github.com/user-attachments/assets/0bbe193e-94e1-4c0b-b5cf-d8588e419818" /><br>
by this code when i send this:<br>
<img width="1205" height="175" alt="image" src="https://github.com/user-attachments/assets/9fd8d117-88e8-480b-a488-35f97d1bb18c" /><br>
what a should be given back as a cookie is the cookie when the values are as the default:<br>
<img width="434" height="19" alt="image" src="https://github.com/user-attachments/assets/e385b0fa-85cf-417d-a2ac-66c86353ef45" /><br>
so i wrote this:<br>
<img width="1100" height="500" alt="image" src="https://github.com/user-attachments/assets/299bc633-59b2-486e-b3c6-9d6c5905707d" /><br>
so this -> {"showpassword":"no","bgcolor":"#ffffff"}<br>
is the value of one side of the xor encryption<br>
to get the other side we will look at the cookie we got back:<br>
<img width="670" height="140" alt="image" src="https://github.com/user-attachments/assets/e2c2be04-6d5f-4b5a-b0c3-0b87a117be01" /><br>
EGAgHwQ1IxYYMSQYGSZxTUksPFVHYDEQCC0%2FGBlgaVVIJDURDSQ1VRY%3D<br>
this is of course after base 64 encoding so let's decode this:<br>
<img width="1100" height="500" alt="image" src="https://github.com/user-attachments/assets/ad9334f2-9aae-4f6e-81da-ab3597e58dcf" /><br>
now that we have the values before and after the xor function all we have to do is xor them a we will be left with the xor key.<br>
So i wrote this script:<br>
<img width="1384" height="238" alt="image" src="https://github.com/user-attachments/assets/f0ecf4b4-ad24-4c2d-bbf5-d157acb51399" /><br>
yes I used IDLE for a bit of extra challenge :)<br>
and this is the output:<br>
<img width="788" height="35" alt="image" src="https://github.com/user-attachments/assets/91607645-0026-47fd-8c6d-10ce7efad7c5" /><br>
clearly the repitting key is -> "kBSw"<br>
so now I can create my own cookie:<br>
<img width="521" height="491" alt="image" src="https://github.com/user-attachments/assets/dbee12db-1947-4dea-a854-27029dcb9547" /><br>
and put it in my next request:<br>
<img width="1211" height="206" alt="image" src="https://github.com/user-attachments/assets/5b695254-a5ac-43dc-a012-1d160b622f19" /><br>
So we get this:<br>
<img width="652" height="270" alt="image" src="https://github.com/user-attachments/assets/c3e2aa91-4601-4ae3-a4ed-a87023a41c19" /><br>
We should have a cookie party<br>
### Level 12:<br>
"Welcome to the jungle"<br>
username: natas12<br>
password: EAGkE8uzFTxeoTT2mMst9Xy7PX6guEng<br>
<img width="1100" height="520" alt="image" src="https://github.com/user-attachments/assets/6be2a730-37f4-44ff-a362-f96fdca20316" /><br>
looks like we can upload jpeg files now<br>
source code:<br>
<img width="704" height="625" alt="image" src="https://github.com/user-attachments/assets/72e0ca1e-207a-4a79-8422-b3791d7a9d0e" /><br>
lets try and upload a web shell.<br>
looks like it will give us an href to access our webshell after uploading so we don't have tow worrie about finding it.<br>
I created the webshell by taking the vulnerable source code from level 9 and making it event more vulnerable:<br>
<img width="800" height="576" alt="image" src="https://github.com/user-attachments/assets/61bcaa5c-31a7-4580-b45b-8848de12dd96" /><br>
let's upload it:<br>
<img width="642" height="182" alt="image" src="https://github.com/user-attachments/assets/9d423575-f431-4dc8-a5a6-4961c2e49e9b" /><br>
and it didn't work:<br>
<img width="273" height="230" alt="image" src="https://github.com/user-attachments/assets/a0dda0a1-8178-406e-80e7-454c4b8f0b5f" /><br>
looks like i missed a part in the source code that changes the file extension to ".jpg" and this is a problem<br>
<img width="480" height="45" alt="image" src="https://github.com/user-attachments/assets/fe8b9edf-eebd-4363-983d-e59861c5db2d" /><br>
looks like it takes the file extension from the given upload name:<br>
<img width="582" height="125" alt="image" src="https://github.com/user-attachments/assets/4cd95adf-794f-4fa5-8f1d-cb42adf824f8" /><br>
let's look at the upload request:<br>
<img width="1100" height="370" alt="image" src="https://github.com/user-attachments/assets/49f90293-5b07-4686-9c8e-947388925b67" /><br>
here is the problem! let's change the ".jpg" to ".php" and send<br>
<img width="648" height="169" alt="image" src="https://github.com/user-attachments/assets/5ca918b1-fe23-4523-be0f-d47a10a3d3c4" /><br>
it worked!<br>
we now have our webshell, excuse me for not changing the txt from level 9 :)<br>
I'm going to run this command -> ` grep -r -E '\b[0-9a-zA-Z]{32}\b' * /etc ;`<br>
because if it ain't broken don't fix it<br>
<img width="456" height="49" alt="image" src="https://github.com/user-attachments/assets/d4677097-5f71-43c1-90b2-0d2e9def36a4" /><br>
and we found our next password!<br>
### Level 13:<br>
"Surf the web"<br>
username: natas13<br>
password: g8ba0olAzaSJuyS4gnmbdVVigAICLG1k<br>
<img width="1917" height="935" alt="image" src="https://github.com/user-attachments/assets/2748675d-ab0b-445e-93af-c1a717cdbd96" /><br>
source code:<br>
<img width="711" height="755" alt="image" src="https://github.com/user-attachments/assets/eaac970c-faad-4021-8d9f-5d9c99f6775f" /><br>
this looks a problem<br>
```
else if (! exif_imagetype($_FILES['uploadedfile']['tmp_name'])) {
        echo "File is not an image";
}
```
lets read about this command<br>
<https://www.php.net/manual/en/function.exif-imagetype.php><br>
this site says that:<br>
<img width="565" height="58" alt="image" src="https://github.com/user-attachments/assets/4ffa17a1-8690-4c5f-b82c-53700b4c675e" /><br>
let's read about jpg signature:<br>
in [wikipedia](https://en.wikipedia.org/wiki/List_of_file_signatures) I found this:<br>
<img width="954" height="144" alt="image" src="https://github.com/user-attachments/assets/f92d3a08-67fc-4f6a-926c-cb248025d134" /><br>
lets try and add it to my webshell file from last level<br>
<img width="637" height="203" alt="image" src="https://github.com/user-attachments/assets/3bfc82a4-9a78-4225-929a-6f558016a1ee" /><br>
it didn't work :(<br>
let's use IDLE to fix it:<br>
<img width="678" height="586" alt="image" src="https://github.com/user-attachments/assets/e2bed258-dbf6-4d4d-9034-b80b19405121" /><br>
this gave me a file to upload:<br>
<img width="856" height="556" alt="image" src="https://github.com/user-attachments/assets/54474b84-fe0a-4224-97a3-b702b50e768b" /><br>
of course i will change the ".jpg" to ".php"<br>
<img width="638" height="217" alt="image" src="https://github.com/user-attachments/assets/96042f5d-9132-426d-a902-65bcb1dfcbee" /><br>
we have a webshell!<br>
again I will use: `grep -r -E '\b[0-9a-zA-Z]{32}\b' /etc`<br>
and we found it!<br>
<img width="432" height="45" alt="image" src="https://github.com/user-attachments/assets/e3b68734-ae83-404c-867b-53ba061e9d9e" /><br>
### Level 14:<br>
"Surf the web"<br>
username: natas14<br>
password: A0xXu2x9FW8rb8OSQ4ei6n5VBbLUz8h8<br>











I








