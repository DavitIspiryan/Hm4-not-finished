# Hm4-not-finished



import self as self class Classroom:
    hours = {} def __init__(self, input1, input2):
        self.book_from = input1
        self.book_to = input2
        def isAvailable(self,since, till):
            if self.book_from < since < self.book_to:
                return False
             if self.book_to > till > self.book_from:
                    return False
             if since < self.book_from and till > self.book_to:
                        return False
                        return True
        @classmethod def adds(cls):
                            cls.hours[self.book_to] = cls.hours[self.book_from]
                            def main():
          res = False my_room = Classroom(1, 4)
                                while res == False:
                                    print ("choose your first time")
                                    firsttime = int(input())
                                    print("choose your second time")
                                    secondtime = int(input())
                                    res = my_room.isAvailable(firsttime, secondtime) main()
