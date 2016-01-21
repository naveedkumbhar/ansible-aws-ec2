This ansible playbook will perform following tasks:

1: createvolume.yml 

    - It will create general purpose ebs volume 
    - size of the volume will be 5 G in region N.Virgnia ( AZ us-east-1b )
    - and device name will be /dev/xvdf 
    You can attach that volume to instance during creating by adding instance id ex: instance: i-xxxxxx
    

2: deletevolume.yml
    - It will Delete volume by volume id.
