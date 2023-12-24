# File Export, Import and Manager

Data can be exported from and imported into CoRA via the File Export/Import and File Manager system. Options for File Export and Import can be viewed under the left navigation bar. This capability is different from the Excel and PDF export that you will find on all data tables within CoRA such as with Search screens and Reports screens.

## File Export 

In order to export data from CoRA, navigage to Left Sidebar Menu -\> File Export/Import-\> File Export. Please note that users can only export data for the current project.

![Navigate File Export](media/file-export-navigate.png)

This will take you to the File Export page. This page lists the different types of files exports available in CoRA. 

### Export Types

***Emport types options available to different role***

| Role              | Available Export Type                                                                                              | 
| ----------------- | ------------------------------------------------------------------------------------------------------------------ |
| anthroropologist  | Specimens,Zones,Measurements,DNA,Pairs,Articulations, Osteometric Sorting                                          |
| org administrator | Specimens,Zones,Measurements,DNA,Pairs,Articulations,Missing Persons, Missing Persons-DCIPS, Osteometric Sorting   |
| mp administrator  | Missing Persons, Missing Persons-DCIPS                                                                             |


![Click on Action](../../assets/screenshots/file-import-export/Export.png)

### Osteometric Sorting

Osteometric sorting uses size and shape to separate bones from one another. Several statistical methods exist; some references for osteometric sorting are shown below.

???+ abstract "References for osteometric sorting"

    - Byrd, John E., and Bradley J. Adams. "Osteometric sorting of commingled human remains." Journal of forensic sciences 48.4 (2003): 717-724.
    - Lynch, Jeffrey James, John Byrd, and Carrie B. LeGarde. "The power of exclusion using automated osteometric sorting: pair‐matching." Journal of forensic sciences 63.2 (2018): 371-380.
    - Warnke‐Sommer, Julia D., et al. "Z‐transform method for pairwise osteometric pair‐matching." Journal of forensic sciences 64.1 (2019): 23-33.

CoRA produces a zip file of osteometric sorting bone measurement files for all long bones. Any osteometric sorting program used to process these files must accept the following fields.


|Attribute               |Description                                                                                           |
|------------------------|-------------------------------------------------------------------------------------------------------|
|se_id                   |The specimen or skeletal element id within CoRA                                                        |
|skeletal_element        |The composite key the specimen or skeletal element                                                     |
|accession_number        |The accession number for the specimen                                                                  |
|provenance1             |The provenance1 for the specimen                                                                       |
|provenance2             |The provenance2 for the specimen                                                                       |
|designator              |The designator for the specimen                                                                        |
|skeletal_bone           |The skeletal bone type                                                                                 |
|side                    |The side: right, left, unsided                                                                         |
|measurements            |Example measuement headers for the femur: Fem_01, Fem_02, Fem_03, Fem_04, Fem_05, Fem_06, Fem_07       |

!!! tip

    Use the osteometric sorting export to download bone measurements formatted for input into the **osteometric sorting tools**.


CoRA creates a background job for the file export process. A notification will appear when the job has completed. You may need to refresh your screen to see the notification. The notification will indicate whether your export was successful or not. The exported records will appear in CoRA under File manager Section.

### File Export Notification

Clicking on a file export button will not result in an immediate file(s) download. Instead, a request is made to CoRA to begin a file export job in the background. This may take several minutes depending on the number of records to be exported and the number of background jobs that are currently queued in CoRA. Once the file export job is competed a real-time notification will be seen under the notifications bell located on the top right header of the CoRA application.      

![Click on Action](../../assets/screenshots/file-import-export/CompletedExport.png)

To get rid of the notification, click on mark as read.

![Click on Action](../../assets/screenshots/file-import-export/MarkAsRead.png)

### Advanced Exports Feature

The anthropologist and mp admin role can only see the export button option, which will export the entire column from that table. The org admin role had both the export and advanced button. The feature of the advanced button is that we can export specific columns from that table to export. Selecting the include timestamp check box, adds the four columns 'created_by,created_at,updated_by,updated_at,deleted_at' in the excel.
 

## File Manager

All files exported and imported into CoRA can be accessed at a central location called the File Manager. The file(s) that you just exported will be located here after CoRA completes the file export job. To access the File Manager, navigage to Left Sidebar Menu -\> File Export/Import-\> File Manager.

![Navigate File Manager](media/file-manager-navigate.png)

The File Manager will list all of the file export/import jobs that have been completed by CoRA with most recent export/import jobs listed first. To download a file export, click download.  A file export does not become available on this page until the requested file export job has been completed by CoRA. 

![Click on Action](../../assets/screenshots/file-import-export/DownloadExport.png)

## File Import

In order to import a file, Navigage to Left Sidebar Menu -\> File Export/Import-\> File Import

![Navigate File Import](media/file-import-navigate.png)

On the file import screen, select the import file type that you wish to upload. A template can be download for the file type that you are importing. CoRA will not allow you to import a file unless the file import type is selected.

![Click on Action](../../assets/screenshots/file-import-export/MissingFileType.png)

The pairs file type is shown as selected in the screenshot below. Click on browse to select a file to upload from your computer. Once selected, hit upload to upload the file to CoRA. 

![Click on Action](../../assets/screenshots/file-import-export/FileUpload.png)

As with file export, CoRA creates a background job for the file import process. A notification will appear when the job has completed. You may need to refresh your screen to see the notification. The notification will indicate whether your import was successful or not. The imported records will appear in CoRA after a successful import. 

![Click on Action](../../assets/screenshots/file-import-export/ImportNotification.png)

### Import Types

This section details the type of file import types availiable to the user. Templates can be downloaded for each import file type on the file import page. Follwoing are the import types that are available to the user.

1. Specimens
2. Zones
3. Measurements
4. DNA
5. Pairs (Results From Osteometric Sorting Tools)
6. Articulations (Results From Osteometric Sorting Tools)
7. Missing Persons
8. Missing Persons-DCIPS

![Select Import Type](media/file-import-select-file-type.png)

The file being imported must contain a specific word depending on the import type. The filename can contain other words and characters, but it must contain one of the following words.  

| Import Type               | Required Word     | 
| ------------------------- | ----------------- |
| Specimens                 | specimens         |
| Zones                     | zone              |
| Measurements              | measurement       |
| DNA                       | dna               |
| Pairs                     | pair              |
| Articulations             | articulation      |
| Missing Persons           | missing OR dcips  |
| Missing Persons - DCIPS   | dcips             |

***Import types options available to different role***

| Role              | Available Import Type                                                                         | 
| ----------------- | --------------------------------------------------------------------------------------------- |
| anthroropologist  | Specimens,Zones,Measurements,DNA,Pairs,Articulations                                          |
| org administrator | Specimens,Zones,Measurements,DNA,Pairs,Articulations,Missing Persons, Missing Persons-DCIPS   |
| mp administrator  | Missing Persons, Missing Persons-DCIPS                                                        |

### File Upload

Click on browse to select a file to upload from your computer. Once selected, click upload to upload the file to CoRA. The upload button will be disabled until the import type selected and file is attached. Both are the mandatory input for the upload to get triggered.

![File Import Upload](media/file-import-upload.png)

!!! tip
    CoRA validates that the type choosen and file name attached match, it will throws an error if they don't match.

### File Import Notification

As with file export, CoRA creates a background job for the file import process. A notification will appear when the job has completed. You may need to refresh your screen to see the notification. The notification will indicate whether your import was successful or not. The imported records will appear in CoRA after a successful import. You can click the eye icon under the Action menu to see the detailed result of the import prcess. It explains how many records were successfully imported and if there were failures it will also provide the reason for the failure rows. Click the green bell sign on the top right coner to view and mark all notifications.

![File Import Notification Button](media/file-import-notification.png)

### Osteometric Sorting  

#### Pairs

A pairs file produced by an osteometric sorting program must have the following fields for upload to CoRA. Only pairs that were **not** excluded should be uploaded to CoRA. 

|Attribute               |Description                                                                                        |
|------------------------|---------------------------------------------------------------------------------------------------|
|se_id                   |The specimen or skeletal element id internal to CoRA.                                              |
|pair_id                 |The specimen or skeletal element id internal to CoRA for the paired element                        |
|se_skeletal_element     |The composite key for the specimen                                                                 |
|se_accession_number     |The accession number for the specimen                                                              |
|se_provenance1          |The provenance1 for the specimen                                                                   |
|se_provenance2          |The provenance2 for the specimen                                                                   |
|se_designator           |The designator for the specimen                                                                    |
|pair_skeletal_element   |The composite key for the paired specimen                                                          |
|pair_accession_number   |The accession number for the paired specimen                                                       |
|pair_provenance1        |The provenance1 for the paired specimen                                                            |
|pair_provenance2        |The provenance2 for the paired specimen                                                            |
|pair_designator         |The designator for the paired specimen                                                             |
|bonename                |The specimen bone type                                                                             |
|compare_method          |The osteometric sorting method used                                                                |
|compare_method_settings |Program settings                                                                                   |
|sample_size             |The size of the reference sample                                                                   |
|pvalue                  |The p-value of the statistical test                                                                |
|num_measurements        |Number of measurements used for the comparison                                                     |
|measurements_used       |The measurements that were used                                                                    |
|measurement_means       |The means of the measurements in the reference population                                          |
|measurement_sd          |The standard deviation of the measurements                                                         |

#### Articulations

A articulations file produced by an osteometric sorting program must have the following fields for upload to CoRA. Only articulations that were **not** excluded should be uploaded to CoRA. 

|Attribute                      |Description                                                                                 |
|-------------------------------|--------------------------------------------------------------------------------------------|
|se_id                          |The specimen or skeletal element id internal to CoRA.                                       |
|articulation_id                |The specimen or skeletal element id internal to CoRA for the articulated element            |
|se_skeletal_element            |The composite key for the specimen                                                          |
|se_accession_number            |The accession number for the specimen                                                       |
|se_provenance1                 |The provenance1 for the specimen                                                            |
|se_provenance2                 |The provenance2 for the specimen                                                            |
|se_designator                  |The designator for the specimen                                                             |
|articulation_skeletal_element  |The composite key for the articulated specimen                                              |
|articulation_accession_number  |The accession number for the articulated specimen                                           |
|articulation_provenance1       |The provenance1 for the articulated specimen                                                |
|articulation_provenance2       |The provenance2 for the articulated specimen                                                |
|particulation_designator       |The designator for the articulated specimen                                                 |
|bonename                       |The specimen bone type                                                                      |
|compare_method                 |The osteometric sorting method used                                                         |
|compare_method_settings        |Program settings                                                                            |
|sample_size                    |The size of the reference sample                                                            |
|pvalue                         |The p-value of the statistical test                                                         |
|num_measurements               |Number of measurements used for the comparison                                              |
|measurements_used              |The measurements that were used                                                             |
|measurement_means              |The means of the measurements in the reference population                                   |
|measurement_sd                 |The standard deviation of the measurements                                                  |


## Missing Persons DCIPS Import

There is currently an issue affecting the Missing Persons DCIPS import. No more than 20,000 rows can be imported at one time, and the fields in the excel file generated by DCIPS are inaccurate.

Less than 20,000 rows at a time must be taken from the DCIPS excel file and pasted into the Missing Persons template. The import must then be run until all the fields have been imported. Currently, there are about 130,000 rows exported from DCIPS, and the import process requires seven separate files.

Another possible solution is to obtain a delta file containing only the changes from the last import. This approach has not yet been tested. 

