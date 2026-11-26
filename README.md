# configurations
Synchronizers, Validators and Custodians could submit issues to configure their public parameters, e.g. name, logo, descriptions.
exSat Foundation will check with the issues and submit pull request to integrate it.

# Synchronizers
There are two types of information that need to be configured for a Synchronizer:

- **Synchronizer Registration Information**: If the mining pool needs to register as a Synchronizer before exSat catches up with the latest BTC blocks, you should add the "mining_addresses" field in the configuration, which contains all the mining addresses of the mining pool. Please note that this information is public on GitHub, and anyone who accesses the current GitHub repository can see it.

- **Synchronizer Identity Information**: Such as name, icon, website, and introduction. Please note that this information is public on the front-end page, and anyone who accesses the Synchronizer front-end page can see it.

Here's an example from a fabricated mining pool:
```
Issue Title:[Mining Pool's Name]Submit mining pool registration information 

Content:
Please provide the following information for Synchronizer.

*Registration info:
Account: coolpool.sat
Mining Address: "tb1qn6f3ngc9a426dzu9qw569yu9vj9ntjza4zjqz3","tb1qn6f3ngc9a426dzu9qw569yu9vj9ntjza4zjqz2"

Display info in Frontend:
*Name: CoolPool
*Logo url: https://cool.network/img/logo.png
Homepage url: https://coolpool.com
Introduction: A cool pool.

```
> All information marked with an * is required. 
Logo Supports PNG and SVG. The recommended minimum size for Logo is 128*128 pixels and the file size should be less than or equal to 1MB. Otherwise, the image will not be merged, and a comment will be left to remind the user to re-upload the logo.

> Please note that if you have multiple mining addresses, please provide them all in the issue , as the requirement for pools to have mined a block within 72 hours to submit BTC blocks to exSat is still in effect during this period. Moreover, if the blocks you upload are the ones you mined, your $XSAT reward can reach up to 50% of the block reward.


# Validators
Validators can configure its information in this way, the informations can be seen by everyone on the front-end interface. 
Here's an example from a fabricated validator:
```
Issue Title:[Validator's Name] Submit validator information 

Content:
Please provide the following information for validator.

*Account:trustgp.sat
*Name: TrustGP
*Logo url: https://trustgp.network/img/logo.png
Homepage url: https://trustgp.com
Introduction: TrustGP is a great asset management groupt.
```
> All information marked with an * is required. 
Logo Supports PNG and SVG. The recommended minimum size for Logo is 128*128 pixels and the file size should be less than or equal to 1MB. Otherwise, the image will not be merged, and a comment will be left to remind the user to re-upload the logo.