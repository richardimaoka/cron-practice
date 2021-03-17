```
crontab -l
no crontab for richardimaoka
```

```
# this gets you into an editor
crontab -e

# then enter the following instruction, which will be saved 
* * * * * echo 'Hello' >> /tmp/test.txt
# you can re-open the above instruction by crontab -e again
```

```
# this prints out what you edited by crontab -e
crontab -l
```
