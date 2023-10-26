# Détection d'intrusion avec Snort sur pfSense

**IDS** : système de **détection** d'intrusion, c'est un service qui surveille le réseau et **alerte** en cas de trafic malveillant,   
mais il ne prend pas de mesure pour bloquer ces attaques.   

**IPS** : système de **prévention** d'intrusion, c'est un service qui **bloque** les attaques sur le réseau.   
____

![image](https://github.com/techerbeatrice/detection_intrusion_snort_pfense/assets/138071140/d7a2b981-e707-470a-96be-011fcc49adb3)

___

![image](https://github.com/techerbeatrice/detection_intrusion_snort_pfense/assets/138071140/4683eb49-fa62-49a9-97fc-9102943d9a94)

![image](https://github.com/techerbeatrice/detection_intrusion_snort_pfense/assets/138071140/c5a2c486-196b-42cf-913f-92668a8562a3)

___

**Installer Snort sur pfSense**  

![image](https://github.com/techerbeatrice/detection_intrusion_snort_pfense/assets/138071140/01e69703-6138-4978-b943-eb7328f35425)

![image](https://github.com/techerbeatrice/detection_intrusion_snort_pfense/assets/138071140/398c39fe-a36d-40f5-a865-6034ffffb2f3)

___

**Accéder au service Snort**  

![image](https://github.com/techerbeatrice/detection_intrusion_snort_pfense/assets/138071140/1010e0c0-d78d-46e8-b2ae-aeb89cf97f72)

____

**Configurer Snort**   

**a - les paramètres généraux**      

![image](https://github.com/techerbeatrice/detection_intrusion_snort_pfense/assets/138071140/1c94e387-0bdf-41e4-aaf7-d8e5fcc9edca)

**b- les updates**   

![image](https://github.com/techerbeatrice/detection_intrusion_snort_pfense/assets/138071140/a8d1e2f6-3150-4488-ae5c-dc4ef75d6161)

warning : pas d'interfaces, il faut en ajouter
___

**c - snort interfaces**     

![image](https://github.com/techerbeatrice/detection_intrusion_snort_pfense/assets/138071140/0066465b-7347-4a62-a3c4-1e31091b3830)

![image](https://github.com/techerbeatrice/detection_intrusion_snort_pfense/assets/138071140/3d765059-8290-4a8d-b503-0ba1f0f00a6f)

![image](https://github.com/techerbeatrice/detection_intrusion_snort_pfense/assets/138071140/ebcecf6b-e3ee-44b5-ab70-8fcc68a143d4)

**d- démarrer snort**  

![image](https://github.com/techerbeatrice/detection_intrusion_snort_pfense/assets/138071140/0fff9155-7cf2-4fc1-a348-2314bfbb6d0e)

_____

**d - Voir les logs (alerts et blocked)**      

![image](https://github.com/techerbeatrice/detection_intrusion_snort_pfense/assets/138071140/6d318c2c-caf1-4034-bdd5-acabbf208eac)


