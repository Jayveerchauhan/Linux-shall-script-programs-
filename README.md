# Linux-shall-script-programs-




# 1. Linux shell script program to create and print the value of variables.

# name="Jayveer chauhan"
# rollno="2115800012(11)"
# course="B.Tech (Hons) Computer Science"
# echo "Name : $name"
# echo "Roll no: $rollno"
# echo "course: $course"

# 2. Linux shell script program to add two numbers.

# a=20
# b=30
# c=`expr $a + $b`
# echo "sum of x and y is  $c"

# 3. shell script program to swap two numbers.
# a=10
# b=20

# echo "Before Swapping"
# echo "a: $a"
# echo "b: $b"

# c=$a
# a=$b
# b=$c

# echo "After Swapping"
# echo "a: $a"
# echo "b: $b"

# 4. Linux shell script program to read two integer numbers and print the subtraction of both variables

# echo "Enter num1: "
# read num1
# echo "Enter num2: "
# read num2
# result=`expr $num1 - $num2`
# echo "Subtraction is: $result"

# 5. Linux shell script program to multiply two numbers

# echo "Enter num1: "
# read num1
# echo "Enter num2: "
# read num2

# multiply=`expr $num1 \* $num2`
# echo "Multiplication is: $multiply"

# 6. Linux shell script program to print program name using command line argument

# echo "Script program Name: $0"

# 7. Linux shell script program to add two numbers using command line arguments

# x=`expr $1 + $2`
# echo "Sum is: $x"

# 8. Linux shell script program to execute 'ls' command

# cd /
# ls

# 9. Linux shell script program to print the current process id
# echo "Current process identifier: $$"

#  10. Linux shell script program to demonstrate the '$#' variable

# echo "Total command line arguments are: $#"

# 11. Write a Shell program to check the given number is even or odd

# echo "Enter a number : "
# read n
# rem=$(( $n % 2 ))
# if [ $rem -eq 0 ]
# then
# echo "$n is even number"
# else
# echo "$n is odd number"
# fi

# 12. Write a Shell program to check and display 10 leap years.

# clear
# echo "LEAP YEAR SHELL SCRIPT"
# echo -n "Enter a year:"
# read year_checker
# if [ `expr $year_checker % 4` -eq 0 ]
# then
# 	echo "$year_checker is a leap year"
# else
# 	echo "$year_checker is not a leap year"
# fi
