# Withdrawing Materials

The staff-portal offers a few applications to help with process of withdrawing materials. Depending on your needs and your comfort with technology, one or more of these applications may prove of use. You should nevertheless be familiar with any official procedures for withdrawing materials, including but not limited to those here:
- [Withdrawal Procedures for Branch Staff](https://docs.google.com/document/d/1l0pWutFbVLB9dnmx_qV98MqlbMM6oKqghVAG6XilZwg/)
- (*If you participate in SSP*) [Sustainable Shelves process document (SSP)](https://docs.google.com/document/d/1aZtyWUJk1GbFyV7EzCCeJSU0YqtPqzfR0TBW4P1XAak/) 

Permissions for the Withdrawal page are separated into three groups:

1. Basic User (`withdrawalUser`)
2. Sustainable Shelves Program (SSP) User (`withdrawalSSP`)
3. Advanced User (`withdrawalSuperuser`)

The guide below is similarly partitioned, to make it easier for those with the respective permissions to find pertinent information.

## Basic User

For a Basic User, the interface looks like this:

![image](https://user-images.githubusercontent.com/39073287/113335536-127fb680-92f3-11eb-873e-b0b44b3b9f13.png)

### Informational display

On the left, from top to bottom, the user is presented with a pink informational display indicating which item `STATUS` codes should never be manually changed in the catalog from what they are to `LIB USE ONLY`. This display is not interactive.

### Barcode scanning form

Underneath that is the primary form which users will interact with. 

Users should scan one barcode at a time into the Barcode text box. 

If they wish any notes to be included with that scan, they can enter notes in in the Notes text box.

They then press `[Submit]`. (If using a calibrated barcode scanner, the scanner automatically includes the equivalent of pressing `[Submit]` after each scan.)

### Message display

![image](https://user-images.githubusercontent.com/39073287/113336114-e284e300-92f3-11eb-8d55-2aa48e6ac71e.png)

After submitting a barcode, the user will be presented with a message in a table below the form. (The table is hidden if no barcode has been scanned during the current session). Users should look here to see if their scan has been successful. Messages are added to the list from the top down, so the most recent messages will appear at the top.

At any time the user may click `[Clear messages]` to clear the accumulated messages.

#### Successful scans

Successful scans will appear in green. The user may move on to scanning the next barcode.

#### Unsuccessful scans

A scan can be unsuccessful for a variety of reasons:

1. The item `STATUS` is not `LIB USE ONLY` in the catalog. 
2. The item is currently checked out.
3. The item has an item-level hold.

These conditions should be addressed in keeping with the Withdrawal Procedures document linked above.

### Scanned barcodes table

![image](https://user-images.githubusercontent.com/39073287/113350562-a0fe3300-9307-11eb-9062-fd81928de1b9.png)

The form and table on the right-hand column display information for items whose barcodes have recently been scanned. The table will only show barcodes scanned by the currently signed-in user. The calendar selections on the form allow the user to set the boundaries for the earliest and latest scans which will show up on the table below. The `Showing` field determines how many items will be shown on the table.

After each scan, the table will refresh its contents automatically. The user may manually refresh the table without having to scan by clicking the `[Refresh]` button.

## SSP User
*Coming soon*

## Superuser
*Coming soon*

