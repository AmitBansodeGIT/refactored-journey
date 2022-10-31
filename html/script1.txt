#!/bin/bash
mkdir /home/ec2-user/createdbyscript
touch /home/ec2-user/createdbyscript/testfile.txt
echo "this is testing" >> /home/ec2-user/createdbyscript/testfile.txt
cd /home/ec2-user/createdbyscript/
ls -lta
cat /home/ec2-user/createdbyscript/testfile.txt
touch /home/ec2-user/script2.sh
echo "#!/bin/bash
mkdir /home/ec2-user/scriptunderscript" >> /home/ec2-user/script2.sh
echo "Creating script2.sh file"




 
chmod 777 script2.sh

./script2.sh


