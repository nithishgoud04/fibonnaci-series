import tkinter as tk

def calculate_fibonacci(n):
    if n <= 0:
        return[]
    elif n == 1:
        return[0]
    elif n == 2:
        return[0, 1]

    fib_series = [0, 1]
    for i in range(2, n):
        next_value = fib_series[-1] + fib_series[-2]
        fib_series.append(next)
    return fib_series 
def display_fibonacci():
    try:
        num_terms = int(entry.get())
        fib_series = calculate_fibonacci(num_terms)
        result_label.config(text = f"Fibonacci series: {fib_series}")
    except ValueError:
        result_label.config(text =  "Please enter a valid integer.")
