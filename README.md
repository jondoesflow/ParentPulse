# ParentPulse
ParentPulse is a Power Platform solution to help automate and streamline repetitive tasks for school administrators

# What is the Power Platform ?

https://learn.microsoft.com/en-us/power-platform/

# What is Parent Pulse?

Please follow my blog post series for more information:

https://www.jondoesflow.com/post/primary-school-automation-solution-introducing-parent-pulse-solution

# What are the Pre-Requisites for this solution ?

1. Power Apps Premium license (for use with Dataverse)
2. A Office 365 mail enabled account to be able to send emails
3. The ability to import solutions into Dataverse enviuronments
4. A [SharePoint Teams Site](https://support.microsoft.com/en-gb/office/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d) for your school
5. A SharePoint document store comprising of the Word templace (weekly newsletter.docx)

# How do I install the Parent Pulse unmanaged zip file ?

1. Download the file from here
2. Go to https://make.powerapps.com
3. Click Solutions on the left hand navigation
4. Click Import Solution in the tool bar at the top
5. Browse to the downaloded location of the zip file
6. Select the Parent Pulse solution and click Open
7. Click Next
8. Click Next
9. Sign in to the relevant connections
10. Add new connections where the red I is
11. Click next
12. For the Weekly News Letter Location, where ever you have created your Teams Site, go there > Documents > Templates and Upload the Weekly News Letter template (see [here](https://www.jondoesflow.com/post/02-primary-school-automation-solution-send-reminders-for-rsvp-records) for the steps to create the template), paste this location in this environment variable, it should look something like:

![image](https://github.com/user-attachments/assets/6fd5008f-40f6-4606-9c64-2bdeafffcd17)

13. Click Import
14. Wait for Import to complete

This completes the installtion.
