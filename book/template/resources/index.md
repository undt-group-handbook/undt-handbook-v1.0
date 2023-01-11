# UNDT Materials database

The materials database, informally called the UNDb, is a tool developed for the UNDT Group in collaboration with the [Solid Mechanics Research Group (SMRG)](https://www.bristol.ac.uk/engineering/research/solids/)). It is hosted by the [Research Data Storage Facility (RDSF)](https://www.bristol.ac.uk/acrc/research-data-storage-facility/) and is accessible from a Microsoft Access client saved on the [Sharepoint](https://uob.sharepoint.com/:f:/r/teams/grp-UNDTGroup/Shared%20Documents/UNDb). It contains data relating to every sample we have stored in the lab, including material, defect types, etc.

## How to get started

The UNDb uses Microsoft Access to store and access the sample database. Usually Access comes pre-installed on University of Bristol managed PCs, however if you need to install it on your device, navigate to the [Microsoft Office Account page](https://portal.office.com/account) (logging in using your UoB details) and install it from there.

### Map the UNDT RDSF folder as a network location

These instructions can also be found on the [RDSF website](https://www.bristol.ac.uk/acrc/research-data-storage-facility/how-to-access-the-rdsf/). You will need to make sure that you have been added to the project by the data steward: for the UNDT project, this is [Paul Wilcox](mailto:p.wilcox@bristol.ac.uk), and make sure that you have the [VPN](https://www.bris.ac.uk/it-services/advice/homeusers/uobonly/uobvpn/howto/) installed if you are not on campus.

From Windows 10, navigate to `This PC`, and select `Map network drive` on the `Computer` tab.

<img align="center" src="https://github.com/ndtatbristol/undt-handbook-v1.0_mgchandler/blob/main/book/template/resources/network drive.png">

Map the folder `\\rdsfcifs.acrc.bris.ac.uk\Ultrasonic_array_data` to an unused drive, and if prompted for a username use the format `uob\<your-uob-username>`.

### Synchronise the UNDT Sharepoint to your own device using OneDrive

Make sure that you have the Sharepoint documents folder synchronised to your personal OneDrive account. To do this, navigate to the group's [Documents](https://uob.sharepoint.com/teams/grp-UNDTGroup/Shared%20Documents/Forms/AllItems.aspx) folder and click `Sync`

<img align="center" src="https://github.com/ndtatbristol/undt-handbook-v1.0_mgchandler/blob/main/book/template/resources/Sync.png">

Navigate to the synchronised folder. Typically, this will be located at `C:\Users\<your username>\University of Bristol\grp-UNDT Group - Documents`, and open the folder `UNDb`. Open the file `UNDb_Client.accdb`, or make a shortcut to this location to access it more conveniently. Note that you must always access the database from this file on the Sharepoint rather than making a copy of it to your own files. This is because many of the lists used to suggest field entries are saved within the client rather than the database: any change or addition you make will only save to the file you use.

### Make sure you have a UNDb login

The login needed to access the UNDb will not be the same as your UoB account. The person currently responsible for maintaining the database is [Matt Chandler](mailto:m.chandler@bristol.ac.uk). If you have not yet received a login, please email Matt to get one.
