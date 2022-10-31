#!/bin/bash
#function calling
addition()
	{
	sum=`expr $1 + $2`
	return $sum
	}
substraction()
	{
	sub=`expr $1 - $2`
	return $sub
	}


#echo " Please enter two numbers"
#read a
#read b

addition $3 $4
substraction $3 $4

echo " Sum is $sum"
echo " Sub is $sub"

