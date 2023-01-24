1. SELECT * 

FROM GescandeData; 
-----------------------
 

2. SELECT Kenteken, Merk 

FROM GescandeData; 
---------------------
 

3. SELECT Kenteken, Cilinderinhoud  

FROM RDW  

WHERE Cilinderinhoud > 2000; 

------------------------------------- 

4. SELECT Kenteken, Merk 

FROM GescandeData 

WHERE Kenteken NOT IN (SELECT Kenteken FROM RDW); 

-------------------------------------- 

5. INSERT INTO GescandeData (Kenteken, Merk, Handelsbenaming) 

VALUES ('1szn01', 'Suzuki', 'Alto Scantest'); 

 ---------------------------------------

6. SELECT Kenteken, Merk 

FROM RDW 

WHERE Cilinderinhoud > AVG(Cilinderinhoud); 

 ---------------------------------------

 
