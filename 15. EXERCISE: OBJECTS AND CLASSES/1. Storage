class Storage:
    storage = []

    def __init__(self, capacity):
        self.capacity = capacity

    def add_product(self, product):
        if self.capacity > 0:
            Storage.storage.append(product)
            self.capacity -= 1

    def get_products(self):
        return Storage.storage
