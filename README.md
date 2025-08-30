def square_numbers(numbers):
    return [n**2 for n in numbers]

if __name__ == "__main__":
    nums = [1, 2, 3, 4, 5]
    print(f"Squares: {square_numbers(nums)}")

