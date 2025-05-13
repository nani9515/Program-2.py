# Program-2.py
def generate_odd_series(a: int):
    series = []
    for i in range(a):
        series.append(2 * i + 1)
    return series

# Example usage:
a = int(input("Enter a positive integer: "))
result = generate_odd_series(a)
print("Output:", ", ".join(map(str, result)))
