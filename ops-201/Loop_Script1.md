#!/bin/bash 

counter=10 
filename="$0" 
filenamefull="$filename$counter" 

while : 
do 
  cp $0 ./"$filenamefull" 
  let "counter+=1" 
  filenamefull="$filename$counter" 
  sleep 1 
done 