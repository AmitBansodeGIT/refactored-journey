#!/bin/bash
#find numbers of digits (Valid up to 3 digit)
if [ $1 -ge 100 -a $1 -lt 1000 ]
	then
	echo " This number id 3 digit number"
else	
	if [ $1 -ge 10 -a $1 -lt 100 ] 
		then 
		echo " This number is 2 digit number"
	else
		if [ $1 -lt 10 ]
		then
		echo " this number is single digit number"
		else
		echo " invalid number"
		fi
	fi
fi

