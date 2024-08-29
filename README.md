# Visual Studio Snippets for Primitive Properties
This guide explains how to install and use Visual Studio snippets for generating primitive property types in C#. Follow these steps to streamline your development process.

## Primitives Types Available

- Integer Numeric Types:
  - Byte, Sbyte, Short, Ushort, Int, Uint, Long, Ulong
- Floating-Point Numeric Types:
  - Float, Double
- Decimal Type:
  - Decimal
- Boolean Type:
  - Bool
- Character Type:
  - Char
- String Type:
  - String

## Step 1: Import the Snippet File into Visual Studio

- Open and Launch Visual Studio
- Open Code Snippets Manager:
  - Navigate to Tools > Code Snippets Manager or press Ctrl+K, Ctrl+B.
- Select Language:
  - Choose C# from the language drop-down list.
- Import the Snippet:
  - Click Import.
- Browse and select the .snippet file you saved earlier.
- Click Finish.

## Step 2: Use the Snippets in Your Code

- Open a C# File:
  - Open or create a C# file where you want to use the snippets.
- Type the Shortcut:
  - Type one of the shortcuts defined in the snippets (e.g., propbool, propbyte, propint, etc.).
- Expand the Snippet:
  - Press Tab or Enter to expand the snippet. The snippet will generate a property with the default name and type.
- Adjust the Property Name:
  - After inserting the snippet, the property name placeholder ($Name$) will be highlighted. Press Tab to navigate to this placeholder and change it if needed.
- Use Multiple Snippets:
  - Repeat the process for other types or additional properties. If you use the same snippet multiple times, Visual Studio will help by highlighting the placeholders for you to update.

## Step 3: Examples

usage :
  - prop{PrimiteType}
  - propi{PrimiteType}
  - propg{PrimiteType}

prop :
  - To Create a Boolean Property
    - Type **propBool** and press Tab twice.
    - The snippet will generate: **public bool MyProperty { get; set; }**
   
propi :
  - To Create a Double Property with Init
    - Type **propiDouble** and press Tab twice.
    - The snippet will generate: **public double MyProperty { get; init; }**

propg :
  - To Create a Decimal Property with private set
    - Type **propgDecimal** and press Tab twice.
    - The snippet will generate: **public decimal MyProperty { get; private set; }**

