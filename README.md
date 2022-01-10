## ResetXcode
shell script for cleaning Derived Data &amp; Caches from Xcode

```shall
sh resetXcode.sh
```

## Find Unused Code

**Create 'New Run Script Phase' on Build Phase**

```shall
file="unused.rb"
if [ -f "$file" ]
then
echo "$file found."
ruby unused.rb xcode
else
echo "unused.rb doesn't exist"
fi
```

