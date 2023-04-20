# DBAII_lab2
1) backup datafile of users tablespace in noarchivelog mode.
![Screenshot (1067)](https://user-images.githubusercontent.com/93229250/233127763-a8ad7f4d-dfc4-4410-b0f1-a25d7ce222f3.png)
![Screenshot (1068)](https://user-images.githubusercontent.com/93229250/233127844-cae9593b-8d95-4454-9c3d-882bf380e04c.png)

2) make the database in archivelog mode.
![Screenshot (1070)](https://user-images.githubusercontent.com/93229250/233130454-5e06dd63-9931-4513-9844-14c2d833a93b.png)

3) backup the datafile of USERS tablespace as copy 
![Screenshot (1072)](https://user-images.githubusercontent.com/93229250/233132757-145f8c57-eb8d-4f3b-8071-01f99022eb16.png)
 
4) backup controlfile and spfile
![Screenshot (1074)](https://user-images.githubusercontent.com/93229250/233133348-15483781-2fca-4d98-95a0-c09c3f1df656.png)

5) take one full level-0 backup
![Screenshot (1076)](https://user-images.githubusercontent.com/93229250/233134639-39d86d36-fabe-441c-adf6-60c4f4e7672e.png)

6) take one incremental cumulative backup
![Screenshot (1078)](https://user-images.githubusercontent.com/93229250/233135244-72d085e4-1714-4449-989f-1e9d2df21ec2.png)

7) take backup of sysaux tablespace
![Screenshot (1080)](https://user-images.githubusercontent.com/93229250/233138375-c56691b9-9e67-4311-8286-7edd3824a56d.png)

8) backup archivelogs created in the last 5 days.
![Screenshot (1082)](https://user-images.githubusercontent.com/93229250/233156198-a60ca9ee-1858-4064-a7e8-6fe00740aaa7.png)

9) list all available archivelog and delete one of them.
![Screenshot (1085)](https://user-images.githubusercontent.com/93229250/233183908-2be725e8-f405-4abf-802e-bd90cf0af5a6.png)
![Screenshot (1086)](https://user-images.githubusercontent.com/93229250/233183920-b82105f6-f2b2-4297-bd49-f6ec1c52b612.png)


11)
list all available backups as below:

 list backup;
 ![Screenshot (1120)](https://user-images.githubusercontent.com/93229250/233253736-eed0682a-45b3-4599-a5e9-326b797ceec9.png)

 list copy;
 ![Screenshot (1119)](https://user-images.githubusercontent.com/93229250/233253647-94161e8f-d9f8-4d8a-a6fc-09dc4a16543c.png)

 list backup of database by backup;
 ![Screenshot (1118)](https://user-images.githubusercontent.com/93229250/233253540-d6bc8ebe-a55f-4242-a5e1-2a98b4f3da3a.png)

 list backup by file;
 ![Screenshot (1117)](https://user-images.githubusercontent.com/93229250/233253465-0e5dce38-7a3a-4254-b2f8-1e00b78beea9.png)

 list backup summary;
 ![Screenshot (1116)](https://user-images.githubusercontent.com/93229250/233253393-22d5df04-8dbe-485e-8bc3-b696bd309ce9.png)

 list archivelog all;
 ![Screenshot (1115)](https://user-images.githubusercontent.com/93229250/233253324-0d3cdf10-0d6a-4849-8bba-6f3d4023976c.png)

 list copy of datafile 1,2;
 ![Screenshot (1114)](https://user-images.githubusercontent.com/93229250/233253241-05888825-f49f-4e84-8428-86743ee2bab1.png)

 list backup of archivelog from sequence 10;
 ![Screenshot (1112)](https://user-images.githubusercontent.com/93229250/233253120-8706f27d-de44-4526-87b6-1cd5f7cc5cdf.png)

 list expired backup;
 ![Screenshot (1111)](https://user-images.githubusercontent.com/93229250/233253052-fc2be9f0-582b-49a3-a836-516de7670461.png)

 report obsolete;
 ![Screenshot (1110)](https://user-images.githubusercontent.com/93229250/233252992-40846c4b-e841-4432-b734-3624b8f13748.png)

 report need backup;
![Screenshot (1109)](https://user-images.githubusercontent.com/93229250/233252927-e315f2bf-1ac3-444d-8a5b-c9303d20f29b.png)


12) do at least 3 switch logfile.
![Screenshot (1109)](https://user-images.githubusercontent.com/93229250/233252815-833db05e-3ac9-4a53-a26a-08ff293563c4.png)

13) connect to rman and list the available archivelogs.
![Screenshot (1106)](https://user-images.githubusercontent.com/93229250/233252418-14e161e8-80c8-48fa-b7c2-03b71f8f9cbc.png)

14) delete the archivelogs by OS command, then do crosscheck and delete expired archivelogs.
![Screenshot (1107)](https://user-images.githubusercontent.com/93229250/233252580-4b684183-6831-4e63-b7bd-8057cb0633a6.png)
![Screenshot (1104)](https://user-images.githubusercontent.com/93229250/233252284-bb4f8c4e-a1c2-41af-be6d-c9249514ed69.png)
![Screenshot (1103)](https://user-images.githubusercontent.com/93229250/233252304-c252019c-d848-40c4-8e04-fee6051342b9.png)
