class Counter:
    def __init__(self):
        self.count = 0  # Initialize count to 0

    def increment(self):
        self.count += 1  # Increment count by 1

# Example usage:
counter = Counter()
counter.increment()
counter.increment()
print(counter.count)  # Output will be 2
