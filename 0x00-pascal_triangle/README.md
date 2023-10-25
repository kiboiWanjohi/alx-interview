<p>Tasks</p>
<p>0. Pascal's Triangle &nbsp;  </p>

<p>Create a function def pascal_triangle(n): that returns a list of lists of integers representing the Pascal’s triangle of n: &nbsp; 
 </p>

<p>Returns an empty list if n <= 0 &nbsp;  </p>
<p>You can assume n will be always an integer &nbsp;  </p>

<p>cat 0-main.py &nbsp;  </p>
<code>
#!/usr/bin/python3
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
<li>
<ul>[1]
[1,1]
[1,2,1]
[1,3,3,1]
[1,4,6,4,1]
</ul>
</li>
<p>guillaume@ubuntu:~/0x00$ &nbsp;  </p>
