# NSDate-Zodiac

Tool to detect zodiac sign

## Use

1.  Add `NSDate+Zodiac.swift` to your project
2.  Call the `zodiac` method in the following way:

<pre>
let date = NSDate(dateString: "1998-03-14")
print(date.zodiac()) // "Fish"
print(date.zodiac().rawValue) // "fish_icon\n"
</pre>