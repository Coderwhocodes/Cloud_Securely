## 1. Introduction:

### 1.1 PURPOSE

The Main Purpose of this is to develop a software that can locally encrypt data before sending it to the cloud, Reducing Data Leaks while the data is sent and keeping it secure.

### 1.3 Intended Audience and Reading Suggestions

We Wish To develop a CLI Based Software That can be used by anyone with just a few commands.

## 2. Overview:

It is very Important to secure Data. Currently Major companies are getting hit by cyber attacks that leads to various data leaks on the web. Data is the Most valuable resouce that we have in todays world surpassing even oil which is second now. This Project Aims to develop a Cloud based Encryped data storage platform where users can lodin and easily transfer thier data after encryping it. The data will be kept securely on the cloud and even if something is leaked, the data will be encrypted leading to a mitigation a risk os data theft.

### 2.1 Customer:

It can be used by anyone ranging from a child to an old aged person since everyone wants their data to be stored securely. Most important of all, people having business and jobs need to store their data on a cloud in a secure manner, so storage in encrypted format will be safer.

### 2.2 Functionality:

● Users will be able to connect to his or her cloud account using his/her unique id which will be created when they sign up in the application.

● Their accounts can be accessed remotely.

● They will be having admin rights to either upload or download their data.

● They will be able to upload their data on the platform locally first in an encrypted section where their data will be encrypted and will be safely uploaded to the cloud.

● They will also be able to access their data using the SSH id and passkey which will be provided to them during encryption, which will be decrypted first, and then they will receive their data on the destination.

--------------------------------------------------------------
G3
--------------------------------------------------------------

## 4. Deliverables

I’ll deliver the following during the course of development:
    • Feature specification
    • Product design
    • Test plan
    • Development document
    • Source code

## 5. Risk Management

### 5.1 Risk Identification

Following will be the risk involved in my project:

1. Even if the files are encrypted before they are sent to cloud for transmission from source to destination, there is a risk that the data can be intercepted on route to its destination.
2. There is no control over data – Most of the cloud services encourages the users to back up data in real time and sometimes a lot of data that was not meant to be shared can be transfered and viewed by unauthorized people.
3. When file is decrypted at the destination source, the original text may not be available anywhere for comparision.
4. Sometimes a user may require a random access to some part of a file, eg. Records.
5. Data loss during file tranfer.

### 5.2 Risk Mitigation

1. The best way to deal with this risk is that the data is encrypted as well as transmitted over a secure connection.
2. Encryption is within the range of 128 to 256-bit to ensure that important data is not viewed .
3. In the communication system, the originator at the source will hold the original text till the receiver acknowledges that the decryption was successfull.
4. There is sequential encryption and decryption.
5. Cloud risk assesment and finding the gaps between perceived security and actual security.
