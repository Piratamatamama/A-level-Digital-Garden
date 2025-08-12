---
{"dg-publish":true,"permalink":"/ch6-security-privacy-data-integrity/"}
---

### Data
1. Security: Prevent unauthorised access
	1. User account
	2. Password
	3. Digital signature
	4. Firewall
	5. Antivirus software
	6. Anti-spyware
	7. Encryption
	8. Biometrics
		1. Fingerprint scan
		2. Retina scan
	9. Risk:
		1. Hacking
		2. Malware
		3. Virus
		4. Worms
		5. Logic bombs
		6. Trojan horse
		7. Bots(iternet bots)
		8. Spyware
		9. phishing
		10. pharming
2. Privacy: Prevent data lost
3. Integrity: Data consistency/ accuracy
	1. Data Validation
		1. Check digit
		2. Limit check
		3. Range
		4. Presence
		5. Existence
		6. Length
		7. Type 
	2. Data Verification
		1. During data entry
			1. Visual check
			2. Double entry
		2. Data transfer
			1. Checksum
			2. Parity check



### Data verification when data transfer:
#### 1. Checksum
- check if data has been changed/ corrupted when data transmission
1. calculation is made from the data, and result is transmitted with the data
2. receiver repeatts the calculation on data
3. compare the result with value received
4. if result same --> no error
5. else: error present: re-transmit



#### 2. Parity Check: Byte/ Block
##### Parity Byte
1. additional bit (parity bit) is allocated to make the number of 1s in byte odd or even to match the agreed parity (even/ odd is agreed before transmission begun)
2. if a byte with odd number of 1 bits is used when the agreed parity is even then thre is an error, need to resend

##### Parity Block
1. Parity is calculated horizontically and vertically