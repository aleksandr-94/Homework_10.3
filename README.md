# Homework_10.3



def is_even(digit):
    """
    Проверить, является ли число четным.
    Возвращает True, если четное, иначе False.
    """
    return digit % 2 == 0

assert is_even(2) == True, "Test1"
assert is_even(5) == False, "Test2"
assert is_even(0) == True, "Test3"

print("Все тесты пройдены!")
