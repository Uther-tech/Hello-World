# Hello-World
This repository is for practicing the GitHub Flow."
My Firstname is Christian and I'm happy to begin here
grades = [ ]
def fizzbuzz2(n):
    """
    Why evaluate i%3 and i%5 twice?
    """
    for i in range(1, n + 1):
        msg = ''
        if i % 3 == 0:
            msg += "Fizz"
        if i % 5 == 0:
            msg += "Buzz"
        if msg:
            print(msg)
        else:
            print(i)
