def add(a, b):
    raise NotImplementedError("add() has not been implemented")


def multiply(a, b):
    raise NotImplementedError("multiply() has not been implemented")
from calculator import add, multiply

assert add(2, 3) == 5
assert multiply(4, 5) == 20

print("All tests passed.")
git add calculator.py test_calculator.py
git status
git commit -m "Add calculator starter application"
git push origin main
