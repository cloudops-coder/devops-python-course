Python Data Types – Notes

In Python, everything is an object, and data types tell us what kind of value an object holds.

🔹 1. Basic Built-in Data Types
1.1 Numbers

int → whole numbers

age = 30       # integer


float → decimal numbers

pi = 3.14      # float


complex → numbers with real + imaginary part

z = 2 + 3j

1.2 String (str)

Text inside quotes (" " or ' ').

Strings are immutable.

name = "DevOps"
print(name.upper())   # DEVOPS
print(len(name))      # 6

1.3 Boolean (bool)

Either True or False.

Often used in conditions.

is_active = True
print(5 > 3)   # True

🔹 2. Collection Data Types
2.1 List

Ordered, mutable (can change), allows duplicates.

Defined with [ ].

tools = ["Docker", "Kubernetes", "Terraform"]
tools.append("Ansible")
print(tools[0])   # Docker

2.2 Tuple

Ordered, immutable (cannot change after creation).

Defined with ( ).

versions = ("v1", "v2", "v3")
print(versions[1])   # v2

2.3 Set

Unordered, no duplicates, mutable.

Defined with { }.

regions = {"us-east-1", "us-west-1", "us-east-1"}
print(regions)   # {'us-west-1', 'us-east-1'}

2.4 Dictionary (dict)

Key-value pairs, mutable, unordered (Python 3.7+ preserves insertion order).

Defined with { key: value }.

config = {"region": "us-east-1", "env": "prod"}
print(config["region"])   # us-east-1

🔹 3. Special Data Type

None → represents the absence of a value.

result = None
print(result)   # None

🔹 4. Type Conversion

Convert between types using built-in functions:

x = "100"
print(int(x))      # 100
print(float(x))    # 100.0
print(str(123))    # "123"

🎯 Quick Summary

Numbers: int, float, complex

Text: str

Logic: bool

Collections: list, tuple, set, dict

Special: None

Python is dynamically typed → type is decided at runtime.