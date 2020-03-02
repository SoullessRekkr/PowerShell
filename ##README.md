# PowerShell
PowerShell Scripts I have created/modified to perform tasks at my internship

Verifies user is in active directory

If they ARE NOT in active directory script continues

If they ARE in active directory scripts runs another level of verification
verifies if they are an Employee or Domain Admin
verifies if they are now a Student

After selecting the method to update the GPO (by DisplayName or Owner Name)

takes in the informations and displays a list of effected GPO's and a count of the GPO's that will be effected by the script

asks if permissions need to be changed as well

if permissions are being changed displays a detailed list of all the GPO permissions changed

when complete outputs a list of changes for the old and new owver and the GPO effected
