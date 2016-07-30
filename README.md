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
