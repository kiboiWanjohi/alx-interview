<p>Tasks</p>
<p>0. Pascal's Triangle</p>

<p>Create a function def pascal_triangle(n): that returns a list of lists of integers representing the Pascal’s triangle of n:</p>

<p>Returns an empty list if n <= 0</p>
<p></p>You can assume n will be always an integer</p>

<p>cat 0-main.py</p>
<code>#!/usr/bin/python3
"""
0-main
"""
pascal_triangle = __import__('0-pascal_triangle').pascal_triangle

def print_triangle(triangle):
    """
    Print the triangle
    """
    for row in triangle:
        print("[{}]".format(",".join([str(x) for x in row])))


if __name__ == "__main__":
    print_triangle(pascal_triangle(5))

 </code>
<p>guillaume@ubuntu:~/0x00$ ./0-main.py
<li>[1]
[1,1]
[1,2,1]
[1,3,3,1]
[1,4,6,4,1]
</li>
guillaume@ubuntu:~/0x00$ </p>
