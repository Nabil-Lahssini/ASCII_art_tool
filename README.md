# ascii_art
The ascii_art is an open-source library that helps you convert any image into an ASCII-art text file.

## How to get it ?
The ascii_art is a python package that you can simply install using the following command:
```
pip install ascii_art
```
## How to use it ?
To use our library in your code, you need to import it and intialize it, that's all. It's easy !
```
## import library
from ascii_art import ascii_generator

## Declaring the path of the input file and the output.
input = "C:\Users\Default\Desktop\image.jpg"
output = "./ascii_art.txt"

## Intialize an instance of the library
instance = ascii_generator.Generator(input=input, output=output)

## Generate the art 
instance.execute()
```