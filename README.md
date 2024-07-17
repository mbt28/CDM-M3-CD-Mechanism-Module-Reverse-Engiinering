# CDM-M3-CD-Mechanism-Module-Reverse-Engineering
CDM-M3 CD Module decoding I2C control

Here you can find some of the I2C communication decoded for this module:
Write/Read address: 18/17

Media_Status(04, 20), (Play_Status, CDin, CKS)
Track Number(03, 4F), (Track#, CKS)
Playing(09, 41), (22 E0 14 63 2C 1F 10 CKS)
Playing_Track(0C, 47) (03 01 00 Track# 55 72 00 00 00 08 CKS)

Play_Status:
	Not_Playing: 0x01,
	Playing: 0x04,
	
CDin:
	CDin0: 0x01,
	CDin1: 0x03,



Screenshot 2024-07-13 141032.png
