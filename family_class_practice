class FamilyInformation:
    def __init__(self):
        self.familyName = "Son"
        self.adjective = "friendly"
        self.money = 100
       
    def setfitstName(self, name):
        self.fitstName = name

    def printFullName(self):
        print("{} {}".format(self.familyName, self.fitstName))        #("", format()) 형식

    def printFullName2(self):
        print("{} {} {}".format(self.adjective, self.familyName, self.fitstName))     #("", format()) 형식

    def addMoney(self, mymoney):
        self.money += mymoney
        return self.money                                           #1. 200들어오면 self.money=100+200, 2. 300또 들어왔으니 self.money=300+300=600됨

    def checkMyMoneywithBonus(self, mybonus):
        sum = self.money + mybonus                                  #sum = 600 + 50 = 650
        return sum
    
    def showMeTheMoney(self):
        bonus = 50
        myTotalMoney = self.checkMyMoneywithBonus(bonus)                                    #bonus=50는 mybonus 인수로 들어감.
        print("{} {}' money is {}".format(self.familyName, self.fitstName, myTotalMoney))   #문자열 감싸는 큰따옴표 안에 일반문자로 인식되는 작은따옴표..

family1 = FamilyInformation()                               
family1.setfitstName("Stephanie")
family1.printFullName2()
family1.addMoney(200)                               #괄호 안의 200은 mymoney로 들어감
family1.addMoney(300)         
family1.showMeTheMoney()                            #Son Stephanie' money is 650

family2 = FamilyInformation()                               
family2.setfitstName("Mibam")
family2.printFullName2()
family2.addMoney(150)
family2.showMeTheMoney()
