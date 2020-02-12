# String Functions
## Input
```cs
firstname = "Steven Clark";
lastname = "Clark";


Console.WriteLine("Clone: " + firstname.Clone());
// Make String Clone
Console.WriteLine("Compare: " + firstname.CompareTo(lastname));
//Compare two string value and returns 0 for true and for false

Console.WriteLine("Contains: " + firstname.Contains("ven")); //Check whether specified value exists or not in string

Console.WriteLine("EndsWith: " + firstname.EndsWith("n")); //Check whether specified value is the last character of string
Console.WriteLine(firstname.Equals(lastname));
//Compare two string and returns true and false


Console.WriteLine("GetHashCode: " + firstname.GetHashCode());
//Returns HashCode of String

Console.WriteLine("GetType: " + firstname.GetType());
//Returns type of string

Console.WriteLine("GetTypeCode: " + firstname.GetTypeCode());
//Returns type of string

Console.WriteLine("IndexOf: " + firstname.IndexOf("e")); //Returns the first index position of specified value the first index position of specified value

Console.WriteLine("ToLower: " + firstname.ToLower());
//Covert string into lower case

Console.WriteLine("ToUpper:" + firstname.ToUpper());
//Convert string into Upper case

Console.WriteLine("Insert: " + firstname.Insert(0, "Hello")); //Insert substring into string

Console.WriteLine("IsNormalized: " + firstname.IsNormalized());
//Check Whether string is in Unicode normalization from C


Console.WriteLine("LastIndexOf: " + firstname.LastIndexOf("e")); //Returns the last index position of specified value

Console.WriteLine("Length:" + firstname.Length);
//Returns the Length of String

Console.WriteLine("Remove: " + firstname.Remove(5));
//Deletes all the characters from begining to specified index.

Console.WriteLine("Replace: " + firstname.Replace('e', 'i')); // Replace the character

string[] split = firstname.Split(new char[] { 'e' }); //Split the string based on specified value


Console.WriteLine("split[0]: " + split[0]);
Console.WriteLine("split[1]: " + split[1]);
Console.WriteLine("split[2]: " + split[2]);

Console.WriteLine("StartsWith: " + firstname.StartsWith("S")); //Check wheter first character of string is same as specified value

Console.WriteLine("Substring: " + firstname.Substring(2, 5));
//Returns substring

Console.WriteLine("ToCharArray: " + firstname.ToCharArray());
//Converts an string into char array.

Console.WriteLine("Trim: " + firstname.Trim());
//It removes starting and ending white spaces from string.
```
## Output