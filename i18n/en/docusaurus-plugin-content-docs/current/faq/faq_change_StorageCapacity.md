---
id: faq_change_StorageCapacity
title: Change Storage Capacity
---

## &#x1F180; How can I change my allocated storage space?

&#x1F150; You need to apply for using large-scale storage.

Refer to [<u>General Analysis Section > Using large-scale storage</u>](/general_analysis_division/largescale_storage) for application details.


## &#x1F180; How is storage currently allocated?

&#x1F150; Execute the `quota` command as shown below to check.

```
$ lfs quota -u your_account /lustre7
Disk quotas for usr your_account (uid ****):
      Filesystem  kbytes   quota   limit   grace   files   quota limit  
grace
        /lustre7 982177580       0 1000000000       - 443208230 0      
0       -
uid **** is using default file quota setting
$
```

For more information, see [<u>"Checking Quota" in the "Using Lustre FS" page</u>](/general_analysis_division/ga_lustre/#checking-quota).


