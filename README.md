def calculate_percentage(part, total):
    if total == 0:
        return 0

    return (part / total) * 100


if __name__ == "__main__":
    completed = 37
    total = 50

    percentage = calculate_percentage(completed, total)

    print("Completed:", completed)
    print("Total:", total)
    print(f"Percentage: {percentage:.1f}%")
