# User Creation & Roles

User accounts can be created by Org Admins, and can be set up under various roles. Certain roles provide specific level of access to
features on the website.

## User Roles

1. Org Administrator
2. Org Manager
3. Anthropologist
4. DNA Analyst
5. Anthropologist - Project Lead
6. Isotope Analyst
7. Historian 
8. Dentist
9. Intern

##Org Administrator
Org Administrator is one of the Users. Below image shows the screen of Org Administrator. The left side bar includes the various modules of the CoRA web application that the Org Administrator can select.  It consists of Dashboard, Specimens, DNA, Isotope and Administration
                                                                                      
![Click on Action](../images/Images_Org_Users_Project/OrgAdmin.png)

The Org Admin takes the responsibility of creating and managing the <b> Users, <b> Projects, <b> Accession, <b> Instruments </b> and <b> Haplogroup </b>.

### User Management 

#### User Creation

1.2.1 Login as Org Administrator

![Login as Org Administrator](../images/Images_Org_Users_Project/loginAdmin.png)

1.2.2 On the left navigation bar, click on the Administration

![Click on Administration](../images/Images_Org_Users_Project/Admin.png)

1.2.3 Under Administration, click on User Management

![Click on User Management](../images/Images_Org_Users_Project/UserManagement.png)

1.2.4 After you click on User Management, you will see list of all users

![Click on User Management](../images/Images_Org_Users_Project/UserList.png)

The user list screen provides the information related to the user such as its Name, Role, Email, Cell Phone, Active Status, Country, Language, Time Zone, IP Address and Last Activity.
In the image above we can see some users have been inactive since a year and some are still active.

1.2.5 On the User Management page, click on Actions, then Create

![Click on Action](../images/Images_Org_Users_Project/Action.png)

1.2.6 Enter the information on the New User creation page (required fields are marked 
with a red asterisk*)

 
Users will be able to change their password once they have logged in. Ensure to check the Active box so that the user account is active and the user can login. Through the "Roles" field, various user roles can be selected such as Org Admin, Anthropologist, Manager, DNA Analyst, Historian, Intern, Isotope Analyst.
![Click on Action](../images/Images_Org_Users_Project/Usercreation.png)

Below are some fields with some validation rule
 
 Element  | Validation Rule  | Required/Optional
 ------------- | -------------| -------------
 First Name  |  Can only contain letters | Required
 Last Name | Can only contain letters and  dash | Required
 Email  |  Should be unique with 255 max char | Required
 Cell phone | Can only contain numbers and dash | Optional
 Role | Choose from the dropdown | Required
 Active Status | Boolean (True or False) | Optional
 Password | Should fulfill all the password requirements | Required

1.2.7 Once all information is entered, click Save, and a message will appear at the top informing the user that the *“User successfully added”*

![Click on Action](../images/Images_Org_Users_Project/Usercreated.png)

### Edit an Existing User

Click on their name in all user list. You will be taken to a read only page of their user profile. 

To Edit their Profile Information - Click "Actions" - "Edit". 
 ![SE Search Categories](../images/skeletalElements/UserEdit.png)
 
The following fields are available on the user edit screen:

 - **Organization**
 - Projects
 - **First Name**
 - **Last Name**
 - Display Name
 - **Email Address**
 - Cell Phone
 - Alt Phone
 - **Active Profile Flag**
 - **Roles**
 - Default Country
 - Default Language
 - Default Time Zone
 - Instruments
 
Required fields are marked with a red asterisk*. Click save when finished editing.
  
To Reset their Password - Click "Reset Password".
 ![SE Search Categories](../images/skeletalElements/PasswordReset.png)
 
Enter the new password in both the fields and change password.
  ![SE Search Categories](../images/skeletalElements/PasswordChange.png)
  

### Project Management

#### Project Creation

1.3.1 Login as Org Administrator

1.3.2 Under Administration, click Project Management

![Click on Administration](../images/Images_Org_Users_Project/ProjectManagement.png)

1.3.3 After you click on Project Management, you will see list of all Projects
![Click on User Management](../images/Images_Org_Users_Project/ProjectList.png)
The Project list screen provides the information related to the project such as its Name, Description, Manager, Start Date, Status and whether it is Public or not.

1.3.4 On the Project Management Page, click on Actions, then Create

![Click on Administration](../images/Images_Org_Users_Project/Projectaction.png)


1.3.5 Enter the information on the New Project creation page (required fields are marked 
      with a red asterisk*)

<small>*The public option enables the public to view the project *</small>

![Click on Administration](../images/Images_Org_Users_Project/Projectcreate.png)

Below are some fields with some validation rule
 
 Element  | Validation Rule  | Required/Optional
 ------------- | -------------| -------------
 Name  |  Can only contain letters and numbers, min:3 and max:255 chars | Required
 Description |Can minimum 3 chars and 255 max chars | Required
 Status Id |  Can only contain numbers| Required
 Start Date | Can only contain date| Required
 Manager Id | Can only contain numbers | Required
 Geo latitude | Can only contain numbers| Required
 Geo Longitude | Can only contain numbers | Required
 Slack Channel | Can only contain numbers and letters | Optional
 Latest MCC Date | Should fulfill all the password requirements | Optional
 Public | Boolean (True or False)| Optional
 Allow users To create Accessions | Boolean (True or False) | Optional
 Isotope Analysis | Boolean (True or False) | Optional
 Zones Autocomplete | Boolean (True or False) | Optional

#####Adding Users to a Project
The Org Admin will be able to add users to specific projects through 'Assigned Users' field. From the dropdown box, the OrgAdmin adds users to the project and clicks save option.

#### Edit Project
1.3.6 After the creation of a Project and adding Users to a Project, the Org Admin can edit the Project.
On the Project Management page, click on Actions, then Edit

![Click on Action](../images/Images_Org_Users_Project/ProjectActions.png)

1.3.7 Edit the needed information on the Project page, and click save
![Click on Action](../images/Images_Org_Users_Project/ProjectEdit.png)


### Accession Management

#### Creating Accession
1.4.1 Login as Org Administrator

1.4.2 Under Administration, click Accession Management

![Click on Administration](../images/Images_Org_Users_Project/AccessionManagement.png)

1.4.3 After you click on Accession Management, you will see list of all Projects along with Key, Accession number, Provenance 1 and Provenance 2 fields.
![Click on User Management](../images/Images_Org_Users_Project/AccessionList.png)

1.4.4 On the Accession Management page, click on actions, and then click create

![Click on Action](../images/Images_Org_Users_Project/AcessionAction.png)

1.4.2 On the create accession page, the Org Admin can choose a specific project from the drop down option to assign the accession details.

![Click on Action](../images/Images_Org_Users_Project/AccessionCreate.png)

On the create accessions page, enter the required information (*required fields are marked with a red asterisk*) for a particular project and click save
After clicking save, the Org Admin will be redirected to the page displaying accession details associated with a specific project.

Below are some fields with some validation rule
 
 Element  | Validation Rule  | Required/Optional
 ------------- | -------------| -------------
 Number  |  Can only contain letters | Required
 Provenance 1 | Can only contain letters, numbers, dash and space | Optional
 Provenance 2 |  Can only contain letters, numbers, dash and space  | Optional



### Instrument Management 

#### Creating Instrument
1.5.1 Login as Org Administrator

1.5.2 Under Administration, click Instrument Management

![Click on Administration](../images/Images_Org_Users_Project/InstrumentManagement.png)

1.5.3 After you click on Instrument Management, you will see list of all Instruments with Code, Module, Category, Reference and Assigned Users fields.
![Click on User Management](../images/Images_Org_Users_Project/InstrumentList.png)

1.5.4 On the Instrument Management page, click on Actions and then click Create.

![Click on Action](../images/Images_Org_Users_Project/InstrumentCreate.png)

1.5.5 On the create Instrument page, enter the required information and click save (required fields are marked 
 with a red asterisk*)

![Click on Action](../images/Images_Org_Users_Project/InstrumentCreate1.png)

 Element  | Validation Rule  | Required/Optional
 ------------- | -------------| -------------
 Code | Can have max 255 chars | Required
 Category |  Can have max 255 chars| Required
 Module|Can have max 255 chars| Required
 Reference | Can have max 255 chars| Optional
 Assigned Users | Can choose from the options available| Optional

The Org Admin will also be able to edit the users associated with the instrument by clicking the dropdown "Assigned Users"

#### Edit Instrument
1.5.6 After the creation of a Instrument, the Org Admin can edit the Instrument.
On the Instrument Management page, click on Actions, then Edit

![Click on Action](../images/Images_Org_Users_Project/InstrumentEdit.png)

1.5.7 Edit the needed information on the page, and click save
![Click on Action](../images/Images_Org_Users_Project/EditInstru.png)


### Haplogroup Management 
#### Creating Haplogroup

1.6.1 Login as Org Administrator

1.6.2 Under Administration, click Haplogroup Management

![Click on Administration](../images/Images_Org_Users_Project/HaplogroupManagement.png)

1.6.3 After you click on Haplogroup Management, you will see list of all Haplogroups with their columns such as Type, Letter, Subgroup and Ancestry.
![Click on User Management](../images/Images_Org_Users_Project/HaplogroupList.png)

1.6.4 On the Haplogroup Management page, click on Actions and then click Create.

![Click on Action](../images/Images_Org_Users_Project/HaploAction.png)

1.6.5 On the create Haplogroup page, enter the required information and click save (required fields are marked 
 with a red asterisk*)

![Click on Action](../images/Images_Org_Users_Project/HaplogroupCreate.png)

Below are some fields with some validation rule
 
 Element  | Validation Rule  | Required/Optional
 ------------- | -------------| -------------
 Type | Can choose from the option available | Required
 Letter |  Can only contain one character from A-Z| Required
 Subgroup|No specified rule| Optional
 Ancestry | Can choose from the option available| Optional
 

#### Edit Haplogroup
1.6.6 After the creation of a Haplogroup, the Org Admin can edit the Haplogroup.
On the Haplogroup Management page, click on Actions, then Edit

![Click on Action](../images/Images_Org_Users_Project/HaploEditAction.png)

1.6.7 Edit the needed information on the page, and click save
![Click on Action](../images/Images_Org_Users_Project/HaploEdit.png)

##Org Manager
Org Manager is one of the Users. Below image shows the screen of Org Manager. The left side bar includes the various modules of the CoRA web application that the Org Manager can select.  It consists of Dashboard, Specimens, DNA and Isotope
 

![Click on Action](../images/Images_Org_Users_Project/OrgManager.png)

##Anthropologist
Anthropologist is one of the Users. Below image shows the screen of Anthropologist. The left side bar includes the various modules of the CoRA web application that the Anthropologist can select.  It consists of Dashboard, Specimens and DNA
                                                                                      
![Click on Action](../images/Images_Org_Users_Project/Anthropologist.png)

##DNA Analyst
DNA Analyst is one of the Users. Below image shows the screen of DNA Analyst. The left side bar includes the various modules of the CoRA web application that the DNA Analyst can select.  It consists of Dashboard, Specimens and DNA
![Click on Action](../images/Images_Org_Users_Project/DnaAnalyst.png)

##Anthropologist Lead
Anthropologist Lead is one of the Users. Below image shows the screen of Anthropologist Lead. The left side bar includes the various modules of the CoRA web application that the Anthropologist Lead can select.  It consists of Dashboard, Specimens and DNA
                                                                                      
![Click on Action](../images/Images_Org_Users_Project/AnthropologistLead.png)

##Isotope Analyst
Isotope Analyst is one of the Users. Below image shows the screen of Isotope Analyst. The left side bar includes the various modules of the CoRA web application that the Isotope Analyst can select.  It consists of Dashboard, Specimens and Isotope
![Click on Action](../images/Images_Org_Users_Project/IsotopeAnalyst.png)

##Isotope 

You can create/view Isotope Batches as an Admin and Manager. In order to view the isotope batches, click on 'Isotope Batches' on left navigation bar
![Click on Action](../images/Images_Org_Users_Project/IsotopeSearch.png)

In order to create a new isotope batch, click on 'New Isotope Batch'

![Click on Action](../images/Images_Org_Users_Project/Isotopecreate.png)

On the Create Isotope Batch page, enter the required information and click save (required fields are marked 
 with a red asterisk*)

![Click on Action](../images/Images_Org_Users_Project/CreateIsotopeBatch.png)

After the isotope batch is created successfully, you 
will receive success message as given  below
![Click on Action](../images/Images_Org_Users_Project/IsotopeAddSuccess.png)

#### Edit Isotope Batch
After the creation of a Isotope Batch, the Org Admin and Manager can edit the Isotope Batch.
On the Isotope Batches page, click on the batch number to edit

![Click on Action](../images/Images_Org_Users_Project/EditIsotopeBatch.png)

Edit the needed information on the page, and click save
![Click on Action](../images/Images_Org_Users_Project/EditIsotopeBatchDetail.png)

Below are some validation rules associated with Isotope Batch
 
 Element  | Validation Rule  | Required/Optional
 ------------- | -------------| -------------
 Lab | Can choose from the option available | Required
 External Case # |  Can only contain letters and numbers| Optional
 Isotope Batch Number|Can only contain letters and numbers| Required
 Status|Either Open, Associating Isotopes, Cleaning, Demineralizing, Removal Humic Acids, Solubilizing, Freeze Drying Collagen, Determining Collagen Yield and closed|Optional
 Cleaning start date | Can only contain Date | Optional
 Label tubes and caps| Boolean (True or False) | Optional
 Remove all visible signs of surface contamination |Boolean (True or False) | Optional
 Ringes sample with dH20 | Boolean (True or False) | Optional
 Sonicate samples with dh2o-cycle1 | Boolean (True or False) | Optional
 Sonicate samples with dh2o-cycle1 Start Date | Date | Optional
 Sonicate samples with dh2o-cycle2 | Boolean (True or False) | Optional
 Sonicate samples with dh2o-cycle2 Start Date | Date | Optional
 Sonicate samples with 95% ethanol | Boolean (True or False) | Optional
 Sonicate samples with 95% ethanol Start Date | Date | Optional
 Sonicate samples with 100% ethanol | Boolean (True or False) | Optional
 Sonicate samples with 100% ethanol Start Date | Date | Optional
 Dry samples start | Boolean (True or False) | Optional
 Dry sample start date | Date | Optional
 Dry samples end | Boolean (True or False) | Optional
 Dry sample end date | Date | Optional
 Cleaning initials | Can only contain letters and numbers | Optional
 Demineralizing Treatment Start | Boolean (True or False) | Optional
 Demineralizing Treatment End | Boolean (True or False) | Optional
 Demineralizing Treatment Start Date | Date | Optional
 Demineralizing Treatment End Date | Date | Optional
 Rinse Demineralized Samples | Boolean (True or False) | Optional
 Removal Humic Acids treatment start | Boolean (True or False) | Optional
 Removal Humic Acids treatment End | Boolean (True or False) | Optional
 Removal Humic Acids treatment start Date | Date | Optional
 Removal Humic Acids treatment End Date | Date| Optional
 Removal Humic Acids treatment rinse 1 start | Boolean (True or False) | Optional
 Removal Humic Acids treatment rinse 1 End | Boolean (True or False) | Optional
 Removal Humic Acids treatment rinse 1 start Date | Date | Optional
 Removal Humic Acids treatment rinse 1 End Date | Date| Optional
 Removal Humic Acids treatment rinse 2 start | Boolean (True or False) | Optional
 Removal Humic Acids treatment rinse 2 End | Boolean (True or False) | Optional
 Removal Humic Acids treatment rinse 2 start Date | Date | Optional
 Removal Humic Acids treatment rinse 2 End Date | Date| Optional
 Removal Humic Acids treatment rinse 3 start | Boolean (True or False) | Optional
 Removal Humic Acids treatment rinse 3 End | Boolean (True or False) | Optional
 Removal Humic Acids treatment rinse 3 start Date | Date | Optional
 Removal Humic Acids treatment rinse 3 End Date | Date| Optional
 Removal Humic Acids treatment rinse 4 start | Boolean (True or False) | Optional
 Removal Humic Acids treatment rinse 4 End | Boolean (True or False) | Optional
 Removal Humic Acids treatment rinse 4 start Date | Date | Optional
 Removal Humic Acids treatment rinse 4 End Date | Date| Optional
 Removal Humic Acids treatment rinse 5 start | Boolean (True or False) | Optional
 Removal Humic Acids treatment rinse 5 End | Boolean (True or False) | Optional
 Removal Humic Acids treatment rinse 5 start Date | Date | Optional
 Removal Humic Acids treatment rinse 5 End Date | Date| Optional
 Solubilizing clean vials and lids | Boolean (True or False) | Optional
 Solubilizing clean vials and lids date| Date | Optional
 Solubilizing add solubale | Boolean (True or False) | Optional
 Solubilizing place in oven | Boolean (True or False) | Optional
 Solubilizing centrifuge tubes | Boolean (True or False) | Optional
 Solubilizing num acid heat treatment | Can only contain numbers | Optional
 Solubilizing num collagen transfers| Can only contain numbers | Optional
 Solubilizing freeze vials| Boolean (True or False) | Optional
 Solubilizing freeze vials date| Date | Optional
 Freeze Drying Collagen on| Boolean (True or False) | Optional
 Freeze Drying Collagen Start| Boolean (True or False) | Optional
 Freeze Drying Collagen End| Boolean (True or False) | Optional
 Freeze Drying Collagen Start Date| Date | Optional
 Freeze Drying Collagen End Date| Date| Optional
 Combined Sample Weight| Boolean (True or False) | Optional