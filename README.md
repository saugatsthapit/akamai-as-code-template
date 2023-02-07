Saugat's Akamai as a Code Lab:


Folders:
1. prod.saugat_aac -> Property Manager Folder
    1. Environments:
        1. prod
            1. Config Name:
                -  prod.saugat_aac
            2. Hostnames:
                - prod.default.ssthapit.training.ranet.me
                - prod.blue.ssthapit.training.ranet.me
                - prod.green.ssthapit.training.ranet.me

2. saugat_aac -> Pipeline Folder
    1. Environments:
        1. qa
            1. Config Name:
                -  qa.saugat_aac
            2. Hostnames:
                - qa.default.ssthapit.training.ranet.me
                - qa.blue.ssthapit.training.ranet.me
                - qa.green.ssthapit.training.ranet.me
        2. prod1
            1. Config Name:
                - prod1.saugat_aac
            2. Hostnames:
                - prod1.default.ssthapit.training.ranet.me
                - prod1.blue.ssthapit.training.ranet.me
                - prod1.green.ssthapit.training.ranet.me
        3. dev
            1. Config Name:
                - dev.saugat_aac
            2. Hostnames:
                - dev.default.ssthapit.training.ranet.me
                - dev.blue.ssthapit.training.ranet.me
                - dev.green.ssthapit.training.ranet.me

        For each environement, variables values are dynamically assinged based on the values in variables.json

    2. templates:
        - Contains all the config rules. main.json being the default rule.
    

List of Edge Hostnames created:
- Didnt create any because of contract limit. Used my existing edgehostname 
- ssthapit-3.edgekey.net

Staging without Spoofing strategy:
- CNAMED to edgekey-staging.net in DNS zone




