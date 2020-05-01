# Cpanel

### Updated 01/05/20

[Return to index](https://github.com/danielrosehilljlm/CloudBackupApproaches)

Rating (/5): ⭐⭐⭐⭐⭐

<p>Clearly exact backup strategies are going to vary according to the nature of your web infrastructure. However, if you're using a simple shared/reseller provider with Cpanel then the process is pretty straightforwrard.</p>

<p>1. Download a full account backup by using the 'Backup' option in Cpanel. Note: this is not the same thing as any proprietary backup/restore scripts that your host may have installed for you, such as JetBackup.

![backup](/images/cpanel_1.png)

<p>2. Generate a full system backup. This will include files, MySQL databases, and everything else you need to restore the Cpanel in the event that you move host (restore process and user access to restore process varies by host.)

![backup](/images/cpanel2.png)

<p>3. Download the archive and store it somewhere else safe on the cloud and on local storage. Some hosts allow you to generate a cloud-to-cloud backup so that you can directly save the backup image onto AWS S3 or some other cloud storage location. 

![backup](/images/cpanel3.png)
