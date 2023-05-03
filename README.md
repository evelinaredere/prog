class Customer:
    def __init__(self, name, balance):
        self.name = name
        self.balance = balance

    def calculate_percentages(self):
        return self.balance * 0.005
