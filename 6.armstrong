#Write a Shell program to check the given integer is Armstrong number or not.

echo "Enter an integer: "
read number
count=${#number}
sum=0
for (( i=0; i<count; i++ ))
do
digit=${number:i:1}
sum=$((sum + digit**count))
done
if [ "$sum" -eq "$number" ]
then
echo "The number $number is an Armstrong number."
else
echo "The number $number is not an Armstrong number."
fi

#OUTPUT
#mlm@mlm-desktop:~/Desktop/Rojin/NW LAB$ chmod +x amstrong.sh
#mlm@mlm-desktop:~/Desktop/Rojin/NW LAB$ ./amstrong.sh
#Enter an integer: 
#153
#The number 153 is an Armstrong number.
