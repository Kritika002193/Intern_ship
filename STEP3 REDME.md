                INSTALLATION OF ORACLE DATABASE SOFTWARE 19C
After the complete installation of OEL(Oracle Enterprise Linux) 7.9
Go To 'Devices' and select 'Insert Guest Additions CD images'
        <img width="836" height="445" alt="image" src="https://github.com/user-attachments/assets/f08d24e2-db0e-4760-b3a6-564f094c9c66" />
CLICK ON 'Run':-
        <img width="777" height="524" alt="image" src="https://github.com/user-attachments/assets/2024b90d-9a75-4925-aacb-906f0df0ede4" />
WAIT FOR THE PROCESSTO END AND HIT Enter:-
        <img width="699" height="536" alt="image" src="https://github.com/user-attachments/assets/e966de50-f775-4f3c-8271-446df7aef550" />
AGAIN,GO TO THE'Devices' menu and:
  1.Choose 'bidirectional' option in 'drag and drop' segment.
  2.Choose 'bidirectional' option in 'shared clipboard' segment.
      <img width="824" height="449" alt="image" src="https://github.com/user-attachments/assets/89aaec8b-c183-4f38-bcc8-32c840650bcf" />
      <img width="856" height="557" alt="image" src="https://github.com/user-attachments/assets/0770f700-7d66-4fda-a4a9-6f82ba93ac4e" />
NOW OPEN A TERMINAL AND RESTART YOUR MACHINE:-
  1.init 6-For rebooting your VM
  2.init 0-For Shutting down your VM
      <img width="722" height="823" alt="image" src="https://github.com/user-attachments/assets/b745150c-ed3a-4f94-9117-bae0efafac51" />
NOW LOGIN TO YOUR MACHINE AND:
  GET TO THE 'Devices' MENU AGAIN
  CHOOSE 'Shared folders settings' in the 'Shared Folders' option:-
        <img width="596" height="788" alt="image" src="https://github.com/user-attachments/assets/d8e5aefe-e41a-41bd-ab3e-6c95ac9fd13f" />
Now click on '+folder' Icon.
Select the software from the location and check on 
AUTOMOUNT AND MAKEPERMANENT
        <img width="650" height="469" alt="image" src="https://github.com/user-attachments/assets/a7d9e507-9a72-42f1-86db-ad1fa3a2bbce" />
ENABLE THE WIRED FOR INTERNET CONNECTIVITY:
        <img width="633" height="237" alt="image" src="https://github.com/user-attachments/assets/84f0651e-12e4-42b5-9d69-b984a0dbab1e" />
Login with 'root' user.
Now check the connection by using 'ping google.com'
OPEN THE LINK GIVEN BELOW AND FIND THE COMMAND AS SHOWN BELOW:
        https://oracle-base.com/articles/19c/oracle-db-19c-installation-on-oracle-linux-7
        Open the link given below and find the command as shown below
        <img width="808" height="297" alt="image" src="https://github.com/user-attachments/assets/9f5098fd-f750-4a4e-a3fa-79dfac8e3990" />
SET THE PASSWORD FOR "oracle" USER.
SET SECURE LINUX TO 'permissive' by editing the "/etc/selinux/config" file,
MAKING SURE THE SELINUX FLAG ISSETAS FOLLOWS:
        <img width="784" height="318" alt="image" src="https://github.com/user-attachments/assets/d32eead9-337f-4d2f-aef7-1e2d4d902831" />
         <img width="799" height="369" alt="image" src="https://github.com/user-attachments/assets/59d2287a-9e4c-4033-a046-2cd9629bb275" />
FIND THE COMMANDS FROM THE ABOVE LINK AND EXECUTE THEM AS FOLLOWS:
          <img width="718" height="186" alt="image" src="https://github.com/user-attachments/assets/ab3c561a-fdba-419b-a9da-4b8bad8efd0d" />
USE COMMAND TO SELECT THE LOCATION OF THE SOFTWARE: "df-h":
          <img width="898" height="557" alt="image" src="https://github.com/user-attachments/assets/40f98d8a-8b00-4ab3-9c8c-58930d80df3e" />
COPY THE LINUX.X64-193999_db_home.zip FILE TO THE DESTINED LOCATION AS GIVEN BELOW.
AS WELL AS CHANGE THE OWNERSHIP AND MOD FOR DIRECTORY '/u01'AND'/u02'.
        <img width="788" height="128" alt="image" src="https://github.com/user-attachments/assets/686080bb-9dc5-4eeb-8dda-cc429b1af991" />
NOW SWITCH THE USER FROM 'root' to 'oracle' AND UNZIP THE .zip FILE THAT IS COPIED IN THE NEW LOCATION.
        <img width="800" height="193" alt="image" src="https://github.com/user-attachments/assets/a235084b-0c35-4aff-bbbf-7b09182d9a9d" />
Now run the RUN Installer file:"./runinstaller"
        <img width="830" height="421" alt="image" src="https://github.com/user-attachments/assets/bb27e9fa-535a-44ce-b9bf-f362f81162f2" />
SELECT ON:'Setup software only'.Click Next
        <img width="734" height="493" alt="image" src="https://github.com/user-attachments/assets/e945c21a-15a2-436e-bede-ae157319bcda" />
Select "Single instance databse installation" option and click Next.
        <img width="708" height="534" alt="image" src="https://github.com/user-attachments/assets/53e0d3d2-f7b8-4521-b77d-9966eddc6097" />
Select 'Enterprise Edition" & Click on Next.
        <img width="700" height="532" alt="image" src="https://github.com/user-attachments/assets/4165b8a7-112b-4feb-a3f9-eed95a89577c" />
Click on next.
        <img width="705" height="578" alt="image" src="https://github.com/user-attachments/assets/e15c8801-8610-4d5c-abda-731d5f60c77c" />
Click on Next again.
        <img width="655" height="510" alt="image" src="https://github.com/user-attachments/assets/672127b2-03af-4728-91c2-2b729ac9a19c" />
Click on Next again.
        <img width="717" height="538" alt="image" src="https://github.com/user-attachments/assets/4000b01f-d88f-49f7-9edc-efa8fca5490d" />
CHECK "Automatically run configuration scripts' and provide the password for 'root' user. Click next.
       <img width="706" height="543" alt="image" src="https://github.com/user-attachments/assets/cd16cd22-f97d-4599-a91a-84bc484d7bec" />
 Check IGNORE ALL & Click on Next.
        <img width="680" height="496" alt="image" src="https://github.com/user-attachments/assets/3dd98f98-2e94-4624-8335-be65047aafdc" />
Click on 'Yes'.
          <img width="695" height="503" alt="image" src="https://github.com/user-attachments/assets/91d1e873-8d63-4a1f-9385-3d7d94f8c02c" />
click INSTALL.
          <img width="728" height="597" alt="image" src="https://github.com/user-attachments/assets/b76b12ae-89f8-4ffb-b4b6-991b2acf7ba4" />
NOW THE FOLLOWING SCREEN WILL APEAR & IT WILL TAKE TIME TO INSTALL THE SOFTWARE.
          <img width="682" height="524" alt="image" src="https://github.com/user-attachments/assets/f9d405d8-23ba-40bf-a27f-35c655038906" />
CLICK ON 'Yes'.
          <img width="691" height="488" alt="image" src="https://github.com/user-attachments/assets/5c62ce49-8312-4e97-883b-e42f93923c3a" />
NOW SELECT 'CLOSE'.
           <img width="730" height="580" alt="image" src="https://github.com/user-attachments/assets/3f355cbd-ec73-4d74-9022-f3a48f6de926" />
RUN THE FOLLOWING HIGHLATED SCRIPTS AS SHOWN BELOW.
            1.OPEN A NEW TERMINAL
            2.LOGIN AS 'ROOT' USER
            3.RUN THE SCRIPTS

<img width="800" height="663" alt="image" src="https://github.com/user-attachments/assets/0e25c966-fa12-44cb-9184-448f78f75f0b" />







        
