# ResetXcode
shell script for cleaning Derived Data &amp; Caches from Xcode


# Find Unused Code
file="unused.rb"
if [ -f "$file" ]
then
echo "$file found."
ruby unused.rb xcode
else
echo "unused.rb doesn't exist"
fi


