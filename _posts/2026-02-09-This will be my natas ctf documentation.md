hello!!!\
let's do a ctf together

### Level 0:
"we are all starting somewhere"\
username: natas0\
password: natas0\
<img width="1100" height="520" alt="image" src="https://github.com/user-attachments/assets/4094b0c6-e6b8-4373-a82b-62869c28de71" />
let's right click and choose:\
<img width="338" height="39" alt="image" src="https://github.com/user-attachments/assets/82878a7c-b71e-4db1-be5a-f40ff08d11b4" />
and BOOM!!!\
<img width="1084" height="366" alt="image" src="https://github.com/user-attachments/assets/45b2dc20-7aef-44f1-8182-93f4461c594f" />
We found the password!
### Level 1:
"moving on"
username: natas1\
password: scfWG6qNEIdzqVyfRwEGXyNUfFZkZeQ7\
<img width="1100" height="520" alt="image" src="https://github.com/user-attachments/assets/a3922bcb-c7be-4818-8b13-f5a74c48baf7" />
looks like we cand right click this time...
but we can press ctrl+U to get to the source page:
<img width="1089" height="389" alt="image" src="https://github.com/user-attachments/assets/e4df494f-f0bf-4e34-a0b3-a5bc4be45947" />
### Level 2:
"This is easy"\
username: natas2\
password: vsDOxoXyq3wckCP1ZmTZ71ngIA606odB\
<img width="1100" height="520" alt="image" src="https://github.com/user-attachments/assets/20b2e262-609c-4f37-b706-0ed8bfc77654" />
We will see about that!
there is actually nothing in the source of the page:\
<img width="1075" height="314" alt="image" src="https://github.com/user-attachments/assets/169803fe-15f8-4ba7-8abc-e7218507cdb9" />
except for that pixel.png that reveals a "files" directory that is probably accessible\
let's try:\
<img width="556" height="330" alt="image" src="https://github.com/user-attachments/assets/5fd47b24-9ce2-416a-bcd9-ade9c91c9c9c" />
nice!
what is in this users.txt file?\
<img width="365" height="152" alt="image" src="https://github.com/user-attachments/assets/16df0ec1-fb01-43e3-9688-ed1e51d78f22" />
### Level 3:
"To the next level"\
username: natas3\
password: K30JrSRHzjxq3paUQuwozY4MNvmNFyhI\
<img width="1100" height="520" alt="image" src="https://github.com/user-attachments/assets/09025669-e216-40cf-830e-747470089353" />
looks the same...\
you know the drill...\
<img width="1083" height="314" alt="image" src="https://github.com/user-attachments/assets/04051063-46fc-468d-91d3-1be9e170df2e" />
after researching long and hard about this "not even google will find it this time" i stumbled across this website:\
<https://developers.google.com/crawling/docs/robots-txt/create-robots-txt>\
which says that google has a web crawler that scans sites and sites can config a robots.txt files to control what it accesses\
so i tried accessing it myself:\
<img width="515" height="121" alt="image" src="https://github.com/user-attachments/assets/e520ab79-46f3-478b-b164-27bad511c81d" />
looks good! let's try this /s3cr3t/ path:\
<img width="579" height="311" alt="image" src="https://github.com/user-attachments/assets/5656bb5d-3853-4e4c-b5d4-faa070a60e6e" />
yesss
<img width="589" height="95" alt="image" src="https://github.com/user-attachments/assets/59d18d22-1133-4385-98d7-233e0262ecda" />
### Level 4:
"This is only getting easier"\
username: natas4\
password: JDrPnuZAKyl6MkiqQGFIddrqpvgOASth\
<img width="1100" height="520" alt="image" src="https://github.com/user-attachments/assets/67674bd4-0e54-46f8-923c-c4c08ab0c1b0" />
looks like it is time to open burp suite!
this is what our request looks like:\
<img width="1211" height="206" alt="image" src="https://github.com/user-attachments/assets/4b4a3333-037d-4db4-9849-e7c391a79962" />
I believe that if i change this 4 in the referer field to 5 I will be granted access:
<img width="627" height="174" alt="image" src="https://github.com/user-attachments/assets/91c5c2a5-2266-43c9-8089-4f3704e7c812" />
I was right!
### Level 5:
"Give me a real challenge"\
username: natas5\
password: e4z2Noy3oqwPJUWzJH0dseN67Cn1sy2M\
<img width="1100" height="520" alt="image" src="https://github.com/user-attachments/assets/0e59913b-4cf7-44ee-bec2-c2151e06b4d1" />
thankfully I'm already in burp suite lets look at the request:\
<img width="1195" height="192" alt="image" src="https://github.com/user-attachments/assets/a6934ae9-15ba-4f7f-9f46-970088395d13" />
This is lying!
let's change it to 1:
<img width="692" height="179" alt="image" src="https://github.com/user-attachments/assets/13e4f2cf-2de5-4339-88db-43d220e91213" />
done!
### Level 6:
"You can't stop me"\
username: natas6\
password: 7mhjtShJAcld2NYbKHEadnhEwRn2P8VT\


