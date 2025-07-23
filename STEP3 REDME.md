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
AS WELL AS 



        
