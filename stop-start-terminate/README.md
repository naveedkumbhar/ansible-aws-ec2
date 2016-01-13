This ansible-play book will perform following tasks:

1: By running this ansible-playbook you can stop,start or terminate instance 

2: all you have to do is just set instance ids, and region

3: wait: yes ( is optional - if you want to wait until proccess complete then add this otherwise it will just execute playbook and return back on terminal.

4: You can stop/start/terminate multiple instances at a time by using this pattern:



instance_ids:

           - 'i-31fb2387'
           
           - 'i-78c870ce'
