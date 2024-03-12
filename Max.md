# Auto Delete downloaded files last modified date more than 15 days

---
 	Task:
	Write PowerShell script to auto delete downloaded files last modified date more than 15 days. By using Task Scheduler every 4hr run PowerShell script and delete the files 
1.	Create one folder in Download folder like name ‘Auto Delete’
![image](https://github.com/MaxDev-5151/SSH-Protocol/assets/159645796/beccf025-a327-4481-ba49-7734437acea2)
2.	Open Chrome Browser > Settings > Downloads
![image](https://github.com/MaxDev-5151/SSH-Protocol/assets/159645796/341108a9-f467-4953-a8b0-9376595161a8)
3.	Change the path click on change button to ‘Auto Deleted’ folder which we are created in Downloads folder
![image](https://github.com/MaxDev-5151/SSH-Protocol/assets/159645796/d3a07c4d-5076-4226-8545-d1d4e320f186)
4.	Open Notepad write script and save this script with .ps1 extension
![image](https://github.com/MaxDev-5151/SSH-Protocol/assets/159645796/b5e81151-66a2-449c-b672-02953c1309fa)
5.  Open local PowerShell and run cd command then we got one error
![image](https://github.com/MaxDev-5151/SSH-Protocol/assets/159645796/8965c5df-efd4-478e-bd21-7117bffcbd41)
6.	After got this error open Administrator PowerShell and run some ‘Execution Policy’ commands
![image](https://github.com/MaxDev-5151/SSH-Protocol/assets/159645796/b2c00502-19f2-4a1f-9cae-fdbbd4a25616)
7.	After that come back to our local PowerShell and try to run our script and check auto delete downloaded files current day to last modified date more than 15 days
![image](https://github.com/MaxDev-5151/SSH-Protocol/assets/159645796/ed7d37d2-b505-486a-a1db-369e43b568e3)
8.	Now In our Windows open ‘Task Scheduler’ and click on ‘Create Task’ 
![image](https://github.com/MaxDev-5151/SSH-Protocol/assets/159645796/9baa2faf-e1ab-4e17-9a5a-54fbf7da7b31)
9.	In General tab enter name for the task and check other fields 
![image](https://github.com/MaxDev-5151/SSH-Protocol/assets/159645796/68696006-3dba-499e-a288-d97a7da46ab9)
10.	After that go to ‘Triggers’ tab > new > select date, time, repeat task every 4hr and then click on OK
![image](https://github.com/MaxDev-5151/SSH-Protocol/assets/159645796/213f00ef-bdec-431f-bb2d-9656e1352ba3)
11.	In Actions Tab:
![image](https://github.com/MaxDev-5151/SSH-Protocol/assets/159645796/9fa693fc-806f-42d8-86ee-0098926c4f71)
12.	Default condition tab (do not change anything)
![image](https://github.com/MaxDev-5151/SSH-Protocol/assets/159645796/8b6cc685-4071-4206-87e8-fd710c57444f)
13.	Also Default ‘Settings’ tab and then click on ‘ok’
![image](https://github.com/MaxDev-5151/SSH-Protocol/assets/159645796/75fefe51-e29d-4076-aed3-0ecb68a9493d)
14.	Before run the task scheduler ‘Task’, In ‘Auto Delete’ folder there are few images which is more than 15 days old.
![image](https://github.com/MaxDev-5151/SSH-Protocol/assets/159645796/f31be486-ee19-4aca-a71d-1a7101cd909b)
15.	After Run the task: last modified date more than 15 days data is deleted
![image](https://github.com/MaxDev-5151/SSH-Protocol/assets/159645796/24307e33-f806-4ede-8358-4b57c010fd03)
