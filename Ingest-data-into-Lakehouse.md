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

![Image](https://github.com/user-attachments/assets/65a3fe3d-eede-4c7a-a221-9476aa67375a)

<br>


