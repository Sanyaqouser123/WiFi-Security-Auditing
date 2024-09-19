# WiFi Security Auditing

## Description

Conducted a WiFi security audit using Aircrack-ng to simulate attacks, evaluate security, and propose defenses. The audit focused on assessing the security of a WPA2 network.

## Objective

Evaluate the security of a WPA2-protected WiFi network by simulating various attacks, identifying vulnerabilities, and proposing effective defenses to enhance network security.

## Tools Used

- **Aircrack-ng**: Used for capturing WPA2 handshakes and attempting to crack the WiFi password.
- **Additional Tools**:  Wireshark, Reaver, Kismet, crunch etc.

## Process

1. **Setup**: Configured the network and tools for the audit.
2. **Data Capture**: Captured WPA2 handshakes using Aircrack-ng.
3. **Attack Simulation**: Simulated a dictionary attack with a custom wordlist.
4. **Analysis**: Analyzed the captured data to identify vulnerabilities and determine the success of the attacks.

## Results

- **Password Type**: The WiFi password was composed of only numeric characters.
- **Network Security**: The target network used WPA2 encryption.
- **Attack Type**: Conducted a dictionary attack using a custom wordlist of numeric passwords.
- **Outcome**: The attack was successful. The correct password, `9820000000`, was recovered and verified.
- **Key Received**: Successfully obtained the WPA2 passphrase, demonstrating the effectiveness of the attack against numeric-only passwords.

## Defense Proposals

To enhance the security of WPA2-protected WiFi networks, consider the following recommendations:

1. **Use Stronger Passwords**:
   - Avoid using passwords composed only of numeric characters. Combine letters (both uppercase and lowercase) with numbers and special characters to create complex passwords.
   - Example: `P@ssw0rd1234!`

2. **Increase Password Length**:
   - Use longer passwords to make brute-force attacks more challenging. A longer password exponentially increases the difficulty of cracking attempts.

3. **Enable WPA3**:
   - Upgrade to WPA3 if possible. WPA3 provides enhanced security features over WPA2, including stronger encryption and better protection against brute-force attacks.

4. **Regularly Update WiFi Passwords**:
   - Periodically change WiFi passwords to minimize the risk of unauthorized access. Ensure new passwords follow best practices for complexity and length.

5. **Monitor and Audit Network Security**:
   - Regularly perform security audits and vulnerability assessments to identify and address potential weaknesses in your network.

6. **Use Additional Security Measures**:
   - Consider using additional security measures such as network segmentation, intrusion detection systems (IDS), and network access controls to further protect your network.

## Images
![1](https://github.com/user-attachments/assets/65e69b98-c7af-4aeb-ab68-60de71b6e8b9)
![2](https://github.com/user-attachments/assets/b3f7e623-49f7-41f2-b4fc-7baddb38e259)
![3](https://github.com/user-attachments/assets/02027b5c-5030-47b8-8b16-49679514a07f)
![4](https://github.com/user-attachments/assets/681428ba-4357-48af-ad40-eb81d88a2548)
![5](https://github.com/user-attachments/assets/5be1efda-0460-48f9-85ea-e17015c75119)
![6](https://github.com/user-attachments/assets/1258c6ff-a081-4008-a29f-9ca080165d6e)
![7](https://github.com/user-attachments/assets/0b3de4d5-6f53-43b8-8818-62241afa7626)
![8](https://github.com/user-attachments/assets/e9d5a1ed-d3a7-4519-9ecc-df5069b629dc)
![10](https://github.com/user-attachments/assets/7d6257fa-5d38-4cbc-87f6-23133680e7d9)
![11](https://github.com/user-attachments/assets/ca2c4ebe-176e-40cf-9764-7cf520df2e26)
![12](https://github.com/user-attachments/assets/f5f7ca00-8e8f-4c47-886d-15248a10df50)

## Conclusion

The WiFi Security Auditing project successfully demonstrated the vulnerabilities associated with using numeric-only passwords for WPA2-protected networks. Through the use of Aircrack-ng and a custom numeric-only wordlist, the project achieved the following:

- **Successful Attack**: The numeric password `9820000000` was cracked, showcasing the ease with which numeric-only passwords can be compromised using brute-force methods.
- **Insightful Findings**: The audit highlighted the critical need for stronger password policies and the importance of using a combination of letters, numbers, and special characters to secure WiFi networks against unauthorized access.

This project underscores the importance of implementing robust security measures and staying informed about the latest security practices. By following the proposed defense recommendations, network administrators can significantly improve the security posture of their WiFi networks and protect against common threats.

The findings and recommendations provided in this audit aim to guide better security practices and foster a more secure network environment.









