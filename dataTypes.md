# Types:
Types are fundamental to any program.

They tell us what our data mean and what operations we can perform on those data.

C++ has extensive support for types:  
1. Primitive types (characters, integers, floating-point numbers, etc.)   
    - Defined by the language itself.  
2. User-defined types  
    - Provides mechanisms that let us define our own data types.

```
Primitive Built-in Types
│
├── Arithmetic Type
│   ├── Integral Types
│   │   └── characters, integers, boolean values, etc.
│   └── Floating-point Types
│       └── float, double, etc.
└── Void (Special Type)

User-Defined Types
```



## Boolean Types
The bool type represents the truth values truth and false.

## Character Types
There are several character types, most of which exist to support internationalization.  
- The basic chacracter type is char.  
- A char is the same size as a single machine byte (8 bits).  
- The remaining character types- `wchar_t`, `char16_t`, and `char32_t` are used for extended character sets.  
- The `wchar_t` type is uranteed to be large enough to hold any character in the machine's largest extended character set.  
- `char16_t` and `char32_t` are intened for unicode characters.  

## Integer Types
They represent integer values of (potentially) different sizes.

`long long>long>int>short`

## Floating-point Types
They represent single-, double-, and extened-precision values.

The standard specifies a minimum number of significant digits.
Typically,
- floats are represented in one word (32 bits)
- doubles in two words (64 bits)
- long doubles in three or four words (96 or 128 bits)