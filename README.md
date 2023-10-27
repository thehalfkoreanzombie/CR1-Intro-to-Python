# My First REAL Code Review

## Alex Wallace

## Description
For this project, I had to create three different functions with docstrings for each of them. For the first function, I had to check a list and return the fourth item on the list. I used try and except to prevent errors in case there were too few items in the list. For the second function, I had to check if a dictionary was empty, and if it wasn't, return the key and value for each item of the dictionary in an f-string. For the last function, I had to use a positional argument, args and kwargs. The positional argument asked for our home planet, the args asked for a varying number of planets, and the kwarg asked for a boolean (True, False) to determine whether or not we believe Pluto is a planet. I also had to create a class called "Cat" and assign the attributes 'color' and 'name' to it. I also created a method called 'meow' for this class, and created two instances of the class. For the first instance, I called the cat's name, and in the second instance, I called for the 'meow' method. 

## Setup/Installation Requirements
In order to set this up, you will need to make a directory for your file and then switch over to that directory. Then, create a virtual environment for python 3 to work in. Change into your virtual environment using source venv/bin/activate. For this project, I used a jupyter lab file (.ipynb), so you will need to install jupyterlab into your virtual environment using the requirements.txt file. Use pip install -r requirements.txt. After doing this, you should be able to read and use the .ipynb file properly 

## Known Bugs
The only potential bug here has to do with the function fourth_place. Since this function would give me an Indexerror if there were less than four items in the list, I used the try/except method. This way, if there were less than four items in the list, it would give the user a string telling them this rather than an error.

As an aside, I did learn a couple of things while writing this code review. First, and most important, I learned not to use undo (ctrl + z) in a jupyter notebook. While writing my dict_sayer function, I used it and it deleted the whole code cell! This was very unfortunate, and made me restart that whole code cell. 

I also tripped up a bit during the 'Cat' class exercise. When establishing my method, I forgot to indent the function into the class itself. So, when I tried the dot notation for calling the method, it wouldn't read. Took me a while to figure this out, but when I rubber-ducked it, I realized the method was not embedded into the class, so there was no way to use dot notation to call it.

I also created a branch before I started writing this README. YAY!!!

## License
Copyright 2023 Alex Wallace

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

