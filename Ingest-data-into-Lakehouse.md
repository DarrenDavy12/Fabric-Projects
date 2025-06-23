## Ingest data into Lakehouse 

### Important: 
#### 1. Lakehouse must be created first! 

![Image](https://github.com/user-attachments/assets/ba320e48-371e-491e-b15b-739886a5ac02)

<br>


#### 2. Select Workspaces in the left navigation pane, and then select your new workspace from the Workspaces menu. The items view of your workspace appears.

#### 3. From the New item option in the workspace ribbon, select Data pipeline.
#### 4. In the New pipeline dialog box, specify the name as IngestDataFromSourceToLakehouse and select Create. A new data factory pipeline is created and opened.

![image](https://github.com/user-attachments/assets/e1ed5759-7f21-48c5-8d03-c37da2e88a6e)


<br>


#### Pipeline Main UI 
![Image](https://github.com/user-attachments/assets/e44cab14-a65d-41c2-8685-c8c0905d829d)


#### 5. Next, set up an HTTP connection to import the sample World Wide Importers data into the Lakehouse. From the list of New sources, select View more, search for Http and select it.

<br> 

![Image](https://github.com/user-attachments/assets/bd146473-ecd6-4158-a9c5-0fb41a63c56b)


<br> 

![Image](https://github.com/user-attachments/assets/eeb0b54d-a06d-497c-8f1d-776ed5000638)



#### 6. In the next step, enable the Binary copy and choose ZipDeflate (.zip) as the Compression type since the source is a .zip file. Keep the other fields at their default values and select Next.

<br>

![Image](https://github.com/user-attachments/assets/78e7d670-0784-4f04-b5fe-55f0abe44cd5)

<br>



#### 7. In the Connect to data destination window, specify the Root folder as Files and select Next. This will write the data to the Files section of the lakehouse.

<br>

![Image](https://github.com/user-attachments/assets/657d8349-4a6e-4dbb-8806-453717d5f87e)

<br>

![Image](https://github.com/user-attachments/assets/664162f7-fa1b-482f-a5d6-85fcac55c35f)



#### 8. Select Next, the destination file format is automatically set to Binary. Next select Save+Run. 
#### You can schedule pipelines to refresh data periodically. 
#### In this tutorial, we only run the pipeline once. The data copy process takes approximately 10-15 minutes to complete.
<br> 

![Image](https://github.com/user-attachments/assets/7344d06d-cdba-4d09-a805-c1666bca4bdb)


<br>


#### 9. You can monitor the pipeline execution and activity in the Output tab. 
#### You can also view detailed data transfer information by selecting the glasses icon next to the pipeline name, which appears when you hover over the name.

<br> 

![Image](https://github.com/user-attachments/assets/49e72a55-8e4a-4da3-9146-60f4e7b0cda1)


#### So I waited for the data transfer to be successfull. 

<br>

![Image](https://github.com/user-attachments/assets/294b8de8-b31d-44d5-b2dd-11565e137113)

<br> 


#### 10. Verify that the folder WideWorldImportersDW is present in the Explorer view and contains data for all tables.

<br>

![Image](https://github.com/user-attachments/assets/30ae5b5e-ca32-4ec8-9ba8-45c690f7f02e)


