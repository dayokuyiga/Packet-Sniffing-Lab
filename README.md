# Packet Sniffing Lab

## Objective

The Packet Sniffing Lab project aimed to understand and analyze network traffic using Wireshark by capturing and filtering different types of network packets.

### Skills Learned

- Capturing and analyzing live network traffic
- Using hex searches to locate specific data within the packets.
- Following TCP streams to track data exchanges.
- Network protocol knowledge and security vulnerability understanding.

### Tools Used

- Network analysis tools (Wireshark) for capturing and examining network traffic.

## Steps

### Screenshot 1: I start Wireshark on Windows ready to capture packets.
![Screenshot 2024-11-02 235738](https://github.com/user-attachments/assets/5d40bb3f-807e-4c54-ac5d-8422977a3ba4)

### Screenshot 2: I applied a filter "DNS" to display DNS packets.
![Screenshot 2024-11-03 000956](https://github.com/user-attachments/assets/457ca9f4-e84d-4764-9779-8b0a71888562)

### Screenshot 3: This screenshot shows the DNS packet for my website that does not exist, and I located it with the info section of the Domain Name System saying "No such name."
![Screenshot 2024-11-03 001249](https://github.com/user-attachments/assets/fa0b3d85-7a6a-495b-ad22-d1cf161dd2e1)


### Screenshot 4: In this screenshot, I applied a filter to display the ICMP packets. 
![Screenshot 2024-11-03 001623](https://github.com/user-attachments/assets/53e858b9-fe2c-45f6-b369-c6b7528e565d)


### Screenshot 5: In this screenshot, I am showing the ICMP packets containing the ping data I sent.
![Screenshot 2024-11-03 001824](https://github.com/user-attachments/assets/3054217c-42e0-4a08-ba05-f585b76c0b16)


### Screenshot 6: This screenshot results from first filtering the packet filter with TLS. Then, I found the first TLS packet associated with Amazon's IP address. After that, I expanded the packet contents, and under the “Transport Layer Security”, I searched in the list and found the list of cipher suites.
![Screenshot 2024-11-03 003122](https://github.com/user-attachments/assets/9dc01860-0b7c-44b9-89f5-e8eeb0d95f80)


### Screenshot 7: The steps I took in this screenshot were as follows: First, I opened a capture file. Second, I went into the file, clicked on edit, and then found a packet to paste hex values in the search bar and confirm the hex value in the drop-down menu. After that, I clicked find to find the specific packet. Third, I right-clicked on the packet that contained the hex values and opened the TCP stream. Lastly, I configured the data to show as Raw.
![Screenshot 2024-11-03 005841](https://github.com/user-attachments/assets/fe3142ea-1101-4afa-8869-b782db51619d)
