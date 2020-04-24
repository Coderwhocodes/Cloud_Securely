# This is a template of Software Requirement Specification

4. Deliverables

I’ll deliver the following during the course of development:
    • Feature specification
    • Product design
    • Test plan
    • Development document
    • Source code

5. Risk Management

5.1 Risk Identification

Following will be the risk involved in my project:

1. Even if the files are encrypted before they are sent to cloud for transmission from source to destination, there is a risk that the data can be intercepted on route to its destination.
2. There is no control over data – Most of the cloud services encourages the users to back up data in real time and sometimes a lot of data that was not meant to be shared can be transfered and viewed by unauthorized people.
3. When file is decrypted at the destination source, the original text may not be available anywhere for comparision.
4. Sometimes a user may require a random access to some part of a file, eg. Records.
5. Data loss during file tranfer.

5.2 Risk Mitigation

1. The best way to deal with this risk is that the data is encrypted as well as transmitted over a secure connection.
2. Encryption is within the range of 128 to 256-bit to ensure that important data is not viewed .
3. In the communication system, the originator at the source will hold the original text till the receiver acknowledges that the decryption was successfull.
4. There is sequential encryption and decryption.
5. Cloud risk assesment and finding the gaps between perceived security and actual security.
