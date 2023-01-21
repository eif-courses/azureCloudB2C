# Azure cloud autorizacijos sistemos B2C konfigūravimas

Paruošiamieji darbai pasirenkame Azure PowerShell CLI atidarius reikia sukurti Storage account, kad dirbti su konsole
<img width="832" alt="pirmas zingsnis" src="https://user-images.githubusercontent.com/8007447/213884913-bee67e28-4e1e-44ae-879c-dc01e3f17fbe.png">

Įvesti komandą ```Register-AzureRmResourceProvider -ProviderNamespace Microsoft.AzureActiveDirectory``` ir spustelėti enter klavišą jeigu viskas tvarkoje gausite tokį pranešimą

<img width="707" alt="trecias veiksmas" src="https://user-images.githubusercontent.com/8007447/213884964-9e10a504-ad98-434b-b50d-f2721fd1d7cb.png">

Pirmas žingsnis pasirinkti Create Resource

![image](https://user-images.githubusercontent.com/8007447/213881814-57796de5-e405-44a3-a6df-8016d101c8a2.png)

Antras žingsnis paeiškos laukelyje suvesti Azure Actice Directory B2C ir pasirinkti šią paslaugą

![image](https://user-images.githubusercontent.com/8007447/213881981-02184b06-3e0c-41bf-ae89-a763675f11bc.png)

Spausti Create ir sekančiame žingsnyje pasrinkti Create new tenant bei suvesti reikiamą informaciją

![image](https://user-images.githubusercontent.com/8007447/213882223-9bf6faa7-f629-4bce-bf48-2a83bc2a87fb.png)

Tada spausti Create 

![image](https://user-images.githubusercontent.com/8007447/213882263-dcdcd506-e3e8-4b4a-ad34-0f9438b3ff73.png)

Jeigu viskas tvarkoje pasirinkti kitą tenant (kaip atskira paskira) 
<img width="830" alt="image" src="https://user-images.githubusercontent.com/8007447/213885218-cef5a08a-e509-48f9-bea6-359abddb7120.png">
Pasirinkti App registrations ir New registration ir suvesti reikiamą informaciją -> spausti Register
![image](https://user-images.githubusercontent.com/8007447/213885478-7e96a777-24d2-4c4c-81ce-3b89a094059b.png)
