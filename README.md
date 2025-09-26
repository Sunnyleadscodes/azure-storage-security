# Azure-storage-security
Hands-on project demonstrating Azure Storage Account configuration, replication options (LRS/GRS/RA-GRS), and secure access management with Access Keys, SAS tokens, and Stored Access Policies

Azure Storage Account Configuration & Security Lab 

Introduction
This hands-on lab focused on configuring and securing an Azure Storage Account. I created a new storage account in the Azure portal, explored replication options (LRS/GRS/RA-GRS), configured access tiers and secure transfers, and then connected to the account using Azure Storage Explorer from a Windows VM. I tested different security controls, including access keys, shared access signatures (SAS), and stored access policies (SAP), to understand how permissions and access can be delegated or revoked. 

Steps Completed

1. Create and Configure a Storage Account Logged into Azure Portal → created a Storage Account with LRS redundancy. Reviewed configuration options such as replication and secure transfer.

2. Connect to VM and Azure Storage Explorer RDP’d into a Windows VM. Installed and connected to Azure Storage Explorer using Azure AD credentials. Created a Blob Container (images) and uploaded sample files.

 3. Manage Access Using Keys Retrieved storage account access keys from the Azure portal. Used the key in Storage Explorer to upload and download files. Rotated the access key → verified access was revoked.
 
 4. Configure Shared Access Signatures (SAS) Generated multiple SAS tokens with different permission levels: Read-only SAS (denied uploads). Read + Write SAS (successful uploads). Tested connectivity in Storage Explorer using SAS URLs. Revoked SAS access by rotating keys.
 
 5. Create and Apply a Stored Access Policy (SAP) Created a Stored Access Policy on the blob container. Attached the SAP to a SAS token → tested upload, delete, and access control. Deleted the SAP to fully revoke access.
 
  Key Skills Demonstrated Azure Storage Account deployment & replication (LRS/GRS/RA-GRS). Blob storage configuration and data operations (upload/download). Secure authentication via Access Keys, SAS Tokens, and SAPs. Role of key rotation and granular access management in cloud security.
  
  Using Azure Storage Explorer for practical management tasks.
  
  Conclusion 
  
  This lab gave me hands-on experience with both administration and security of Azure Storage Accounts. I learned how redundancy options protect data, and how granular access control (keys, SAS, SAP) strengthens security for cloud resources. Ok remember this please give me a description and reposiory name I can put for it in gut hub.
