# hello-word
This is my first Github experiment

[root@localhost html]# cat /server/scripts/awk_test.sh 
#!/usr/bin/bash

x=$1
y=$2

read -p 'please input number1 and number2:' x y

awk -vn1=$x -vn2=$y 'BEGIN{print n1+n2}'
awk -vn1=$x -vn2=$y 'BEGIN{print n1-n2}'
awk -vn1=$x -vn2=$y 'BEGIN{print n1*n2}'
awk -vn1=$x -vn2=$y 'BEGIN{print n1/n2}'
