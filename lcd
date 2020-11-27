class lcd:

    numbers = {
        "0": "._.|.||_|",
        "1": ".....|..|",
        "2": "._.._||_.",
        "3": "._.._|._|",
        "4": "...|_|..|",
        "5": "._.|_.._|",
        "6": "._.|_.|_|",
        "7": "._...|..|",
        "8": "._.|_||_|",
        "9": "._.|_|..|"
        }

    def __init__(self, num):
        self.num = str(num)
        self.len = len(self.num)

    def global_func(self):
        i = 0
        while i < 3:  # number of rows
            for pom in self.num:
                val = self.numbers[pom]
                print(val[i*3: i*3+3], end="")
            print("")
            i = i + 1
        return 0


one = lcd(98652)  # number to print
one.global_func()
