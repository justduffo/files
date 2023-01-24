SELECT * 

FROM GescandeData; 

 

SELECT Kenteken, Merk 

FROM GescandeData; 

 

SELECT Kenteken, Cilinderinhoud  

FROM RDW  

WHERE Cilinderinhoud > 2000; 

 

SELECT Kenteken, Merk 

FROM GescandeData 

WHERE Kenteken NOT IN (SELECT Kenteken FROM RDW); 

 

INSERT INTO GescandeData (Kenteken, Merk, Handelsbenaming) 

VALUES ('1szn01', 'Suzuki', 'Alto Scantest'); 

 

SELECT Kenteken, Merk 

FROM RDW 

WHERE Cilinderinhoud > AVG(Cilinderinhoud); 

 

 
