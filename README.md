# while-loop-linux-shell-script
#### While loop example in shell script 

```diff
#!/bin/bash
echo "while Loop"
a=0
while [ "$a" -lt 10 ]
do 
      echo "Loop is running $a"
      a=`expr $a + 1`
```

#### Run this script
###### On our Linux machine open a text editor (vim) and copy this code, save the vim editor
###### Check permission of the script, chnage by typing: chmod ug+x file.sh
###### Now Run the script: ./file.sh








