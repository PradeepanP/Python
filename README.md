PYTHON:

PYTHON OBJECTS AND DATA STRUCTURES BASICS:

DATA TYPES:

int (3,30,300)  whole numbers
float (2.3,4.3) nummbers with decimal  point
string "hello"  ordered sequence of characters
list [10,"hey"] ordered sequence of objects
dict {"mykey" : "value"} Unordered key value pairs
tup (10,"hey")  ordered immutable sequence of objects (cannot change the values)
set ("a","b")   unordered collection of unique objects
bool            Logical values indicating TRUE or FALSE

RULES FOR VARIABLE NAMES:

-> names cannot start with a numbers
-> there should not be any space between variables, instead use(_) this
-> cannot use any symbols
-> lowercase are prefferable
-> avoid using words having special meaning (list,set)

->Python is a "DYNAMIC TYPING" - reassign variables to different datatype
a = 12 , type(a) results in int

STRINGS:

str[]
-> sequence of characters using double or single quotes , 'hello' or "hello"
-> ordered sequence so we can use indexing and slicing to grab the sub sections of the string.
-> indexing helps us to grab specific location.
-> INDEX - positive index(0,1,2,3,4) and reverse index (0,-4,-3,-2,-1)
-> SLICING - allows to grab a part of string 'slice' [start:stop(before this value):step(the jump we are taking)
-> Immutability
-> INDEXING - my_string='hello' - my_string[2] gives 'l'
-> my_string = 'abcdefghij'   my_string[3:6] gives 'def'
-> my_string[2(start from) : 6(go upto) : 2(step size) ]
-> my_string[:: -1] gives (jihgfedcba)

.format()
-> to insert in between string

LISTS:
-> list are ordered sequences that hold variety of objects
-> mutable

DICTIONAIRES:

