# ESBPII
ESBPII Labs (AWS)

01. What is AWS ?

Amazon Web Services (AWS) is a secure cloud services platform which is offering computer power, database storage, content delivery and other functionality to help businesses scale and growth.
                                                                      - AWS -

1.1 Advantages in AWS

          * Low Cost
          * Agility and Instant Elasticity
          * Open and Flexible
          * Secure

1.2 AWS Solutions

          * Application Hosting
          * Websites
          * Backup & Storage
          * Enterprise IT
          * Content Delivery
          * Databases

02. Create Amazon EC2 Windows Instance

2.1 Prerequisites
      
          * Create Amazon Web Service Free tier account
          * Good Internet connection

2.2 Launch an Instance & Connect

          * Open the Amazon EC2 console at https://console.aws.amazon.com/ec2/ and Select EC2 link.
          
![db_1](https://cloud.githubusercontent.com/assets/17094710/17266617/03b9bd2a-5618-11e6-9ec9-32257a4eda2e.png)

          * Select Launch Instance from the console dashboard.
          
![win_1](https://cloud.githubusercontent.com/assets/17094710/17266668/ca8fceee-5618-11e6-980f-8be7fd3ce02d.png)         

          * Select the AMI (Amazon Machine Image) for Microsoft Windows Server 2012 R2 Base or Microsoft Windows Server 2008 R2 Base.

![win_2](https://cloud.githubusercontent.com/assets/17094710/17266669/ca93e470-5618-11e6-9747-65c4b9d34b9e.png)

          * Select the t2.micro type, which is selected by default in Free tier plan and choose Review and Launch button to further configuration.
          
![win_3](https://cloud.githubusercontent.com/assets/17094710/17266670/ca984466-5618-11e6-8705-eb29ca99282a.png)

          * Select or Enter suitable instance details in Configure Instance Details tab and choose Review and Launch.

![win_4](https://cloud.githubusercontent.com/assets/17094710/17266671/ca9c61b8-5618-11e6-8a05-6bad2daa36bd.png)

          * Select an existing security group or Create a new security group for the instance in Configure Security Group tab and click Review and Launch button.

![win_5](https://cloud.githubusercontent.com/assets/17094710/17266672/ca9e83bc-5618-11e6-9140-a97618a503a7.png)

          * Review all the configured details in Review Instance Launch tab and Select Launch button.

![win_6](https://cloud.githubusercontent.com/assets/17094710/17266673/caa0ddec-5618-11e6-9a78-d2a2fcd26ff6.png)

          * Then aws is launching the Windows AMI instance according to the configured details.
          
![win_7](https://cloud.githubusercontent.com/assets/17094710/17266674/cabab12c-5618-11e6-8956-445a7a56214d.png)

          * After launching Windows AMI, Users can connect with Windows instance by clicking Connect button. Then it will prompt window to download Remote Desktop File and user credentials.
          
![win_8](https://cloud.githubusercontent.com/assets/17094710/17266675/cabb099c-5618-11e6-91ab-f76f052bb7e9.png)


03. Create Amazon EC2 Linux Instance

3.1 Prerequisites
      
          * Create Amazon Web Service Free tier account
          * Good Internet connection

3.2 Launch an Instance & Connect

          * Open the Amazon EC2 console at https://console.aws.amazon.com/ec2/ and Select EC2 link.
          
![db_1](https://cloud.githubusercontent.com/assets/17094710/17266617/03b9bd2a-5618-11e6-9ec9-32257a4eda2e.png)

          * Select Launch Instance from the console dashboard.
          
![lin_1](https://cloud.githubusercontent.com/assets/17094710/17266917/44548ed8-561c-11e6-9271-1903eef67617.png)

          * Choose an Linux Amazon Machine Image (AMI) which has labeled as “Free tier eligible” and click Select button.

![lin_2](https://cloud.githubusercontent.com/assets/17094710/17266918/44573872-561c-11e6-8d4a-6e8b6ef6b691.png)

          * On the Choose an Instance Type tab, select the t2.micro type which is selected by default in “Free tier plan” in aws. And click Review and Launch button.

![lin_3](https://cloud.githubusercontent.com/assets/17094710/17266919/44596872-561c-11e6-9c8b-b9356c7c4793.png)

          * Select or Enter suitable instance details in Configure Instance Details tab.
          
![lin_4](https://cloud.githubusercontent.com/assets/17094710/17266920/445d8a56-561c-11e6-9b0a-0f829bbb5d93.png)

          * Select an existing Security group or Create a new Security group for the Linux instance in Configure Security Group tab and Click Review and Launch button.
          
![win_5](https://cloud.githubusercontent.com/assets/17094710/17266672/ca9e83bc-5618-11e6-9140-a97618a503a7.png)
          

          * Review all the Configured details in Review Instance Launch tab and Select Launch button.

![lin_5](https://cloud.githubusercontent.com/assets/17094710/17266921/44614bbe-561c-11e6-8ba1-721244f9332a.png)

          * When prompted for a key pair, Select Choose an existing key pair or Create new key pair and download .perm file to the PC and save in secure place. Also change the permission of .pem file to 400. (chmod 4000 <path/to/.pem/file>)
          
![lin_6](https://cloud.githubusercontent.com/assets/17094710/17266922/4462f702-561c-11e6-9457-4b1c5b4c1ee8.png)

          * After launching Linux AMI, Users can connect with the instance by using key pair.

![lin_7](https://cloud.githubusercontent.com/assets/17094710/17266923/44848138-561c-11e6-9ce0-7479b5ecc655.png)


04. Create Amazon RDB MySQL Database Engine

4.1 Prerequisites
      
          * Create Amazon Web Service Free tier account
          * Good Internet connection

4.2 Launch DB Instance

          * Sign in to the AWS Management console and open the Amazon RDS console at https://console.aws.amazon.com/rds/ .

![db_1](https://cloud.githubusercontent.com/assets/17094710/17267066/157b93e2-561f-11e6-8792-eb7a546b88f4.png)

          * Select the region in where do you want to create the Database instance.

![db_2](https://cloud.githubusercontent.com/assets/17094710/17267068/15bfc198-561f-11e6-8222-f757e5310c9f.png)

          * Click Get Started Now to start the Launch DB Instance wizard.

![db_3](https://cloud.githubusercontent.com/assets/17094710/17267070/15c691bc-561f-11e6-88c1-ed2e9047f5f2.png)

          * Select preferred Database engine to launching and Click Select button.

![db_4](https://cloud.githubusercontent.com/assets/17094710/17267069/15c644b4-561f-11e6-8382-5f3c5608854d.png)

          * Select the correct plan and Click Next Step button.

![db_5](https://cloud.githubusercontent.com/assets/17094710/17267071/15c94d76-561f-11e6-85bc-d35524daa194.png)

          * Enter or Select Database specific details in Specify DB Details tab and Click Next Step button
![screenshot from 2016-07-23 18-13-12](https://cloud.githubusercontent.com/assets/17094710/17267129/ee81317e-561f-11e6-931b-fdaa45beaf9e.png)
![db_7](https://cloud.githubusercontent.com/assets/17094710/17267072/15ccfa20-561f-11e6-80c3-523b24c85332.png)

          * Configure advanced settings in next tab and Click Launch DB Instance button.

![screenshot from 2016-07-23 18-14-46](https://cloud.githubusercontent.com/assets/17094710/17267153/3378d2a0-5620-11e6-8da2-d4ed200a6bf7.png)
![screenshot from 2016-07-23 18-14-54](https://cloud.githubusercontent.com/assets/17094710/17267158/5b8f5048-5620-11e6-98ea-6d6f5c0f3e83.png)
![db_10](https://cloud.githubusercontent.com/assets/17094710/17267067/15a71f44-561f-11e6-94a9-3f60503e13a6.png)

          * After launching DB instance, Users can connect to the database by using DB Instance name, Master Username and Master Password.
          
![screenshot from 2016-07-23 18-15-28](https://cloud.githubusercontent.com/assets/17094710/17267167/92c3e970-5620-11e6-93f1-1d2a34787f62.png)

          
05. References

          * AWS - 
          * Google -
