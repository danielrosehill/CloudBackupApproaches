# Github

### Updated: 11/05/20

[Return to index](https://github.com/danielrosehilljlm/CloudBackupApproaches)

Rating (/5): ⭐⭐⭐⭐

## Main method

Under 'account settings' there is an option called 'Export accound data':

![](/images/gh1.png)

Clicking the 'New export' button will generate an export containing all the user's repositories and metadata.

It will be available for download for 7 days.

A few minutes later the user receives an email like this:

![](/images/gh3.png)

The export, which is delivered as a .tar.gz archive, will contain three JSON files and one archive containing all the uesr's repositories:

![](/images/gh4.png)

The directory at 

```
/repositories
```

Contains all the user's repositories:

![](/images/gh5.png)


## Workaround

A  user can also simply compress and download an archive of all his/her repositories, although this will not capture the user metadata.


![](/images/gh2.png)
