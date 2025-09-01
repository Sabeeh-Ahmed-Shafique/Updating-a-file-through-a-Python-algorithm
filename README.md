## Project Overview
At my organization, access to restricted content is controlled with an allow list of IP addresses. The "allow_list.txt" file identifies these IP addresses. A separate remove list identifies IP addresses that should no longer have access to this content. I created an algorithm to automate updating the "allow_list.txt" file and remove these IP addresses that should no longer have access.

<br><br>

- I performed the following tasks:
<br><br>
  
- Open the file that contains the allow list.

  <img width="1150" alt="PPA-S1" src="https://github.com/user-attachments/assets/4c412e05-16ab-454c-9ba6-155f2f9a3b8d" />
<br>

- Read the file contents.

  <img width="1150" alt="PPA-S22-A" src="https://github.com/user-attachments/assets/37a4b628-db2b-47b7-b128-b5623760c00d" />
 
  <img width="1150" alt="PPA-S4-B" src="https://github.com/user-attachments/assets/ee19721a-571c-4743-baeb-1d83af646f4e" />
<br>

- Convert the string into a list.
 
  <img width="1150" alt="PPA-S3" src="https://github.com/user-attachments/assets/bbef4f03-06ec-4308-bbfd-f25b2d11021e" />
<br>

- Iterate through the remove list.

  <img width="1150" alt="PPA-S4-A" src="https://github.com/user-attachments/assets/b45931ad-8c92-4821-a947-5e878cc8d701" />

  <img width="1150" alt="PPA-S4-B" src="https://github.com/user-attachments/assets/6a738910-22d9-4c09-82dc-0472724701e0" />
<br>

- Remove IP addresses that are on the remove list.

  <img width="1150" alt="PPA-S5-A" src="https://github.com/user-attachments/assets/3176b487-58eb-495a-976d-f2c5d1ac5c28" />

  <img width="1150" alt="PPA-S5-B" src="https://github.com/user-attachments/assets/c799ad32-b557-4c96-aa89-fba557973126" />
<br>

- Update the file with the revised list of IP addresses. 

  <img width="1150" alt="PPA-S6-A" src="https://github.com/user-attachments/assets/706811a6-caaf-4744-b996-e2a7caf4eb76" /> 

  <img width="1150" alt="PPA-S6-B" src="https://github.com/user-attachments/assets/e2271855-7262-4f6b-9c2f-051ff3557d15" />

  <img width="1150" alt="PPA-S6-C" src="https://github.com/user-attachments/assets/1c981a63-91f4-4cc7-83a2-55a2ec3babe5" />
<br>

#### Summary

I created an algorithm that removes IP addresses identified in a remove_list variable from the "allow_list.txt" file of approved IP addresses. This algorithm involved opening the file, converting it to a string to be read, and then converting this string to a list stored in the variable ip_addresses. I then iterated through the IP addresses in remove_list. With each iteration, I evaluated if the element was part of the ip_addresses list. If it was, I applied the .remove() method to it to remove the element from ip_addresses.. After this, I used the .join() method to convert the ip_addresses back into a string so that I could write over the contents of the "allow_list.txt" file with the revised list of IP addresses.


---


[Update a file through a python algorithm]()


To access the complete document, please consider the above link. 
