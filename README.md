print('''
           __   __   ___       __           ___       __               __                 __               ___ 
 /\  |\ | |  \ |__) |__  |  | /__`    \  / |__  |\ | |  \ |__| | |\ | / _`     |\/|  /\  /  ` |__| | |\ | |__  
/~~\ | \| |__/ |  \ |___ |/\| .__/     \/  |___ | \| |__/ |  | | | \| \__>     |  | /~~\ \__, |  | | | \| |___ 
                                                                                                               ''')

item1=['MountainDew(3.50);001']
item2=['DoctorPepper(5.00);002']
item3=['Sevenup(2.00);003']
item4=['Cola(4.00);004']
item5=['Juice(2.50);005']
item6=['IceTea(6.00);006']
item7=['Water(1.00);007']
item8=['Miranda(3.00);008']
item9=['Pepsi(3.00);009']
item10=['Sprite(3.50);010']
print("Welcome to the liquid refreshment vending machine")
print("Item\tPrice\tCode")
print(item1)
print(item2)
print(item3)
print(item4)
print(item5)
print(item6)
print(item7)
print(item8)
print(item9)
print(item10)
x=str(input("--------------------\nEnter the product code:\n"))
if x=='001':
    print('You have chosen MountainDew!')
    y=float(input("pay the amount:\n"))
    MountainDew = 3.50
    if y > MountainDew:
        print("Take your change with your selected item: ",y - MountainDew)
    elif y<MountainDew:
        print("Not enough money")
        print("Amount refunded")
    elif y==MountainDew:
        print('Here is your Mountaindew')
elif x=='002':
    print('You have chosen DoctorPepper!')
    y=float(input("pay the amount:\n"))
    DoctorPepper = 5.00
    if y > DoctorPepper:
        print ("Take your change with your selected item: ",y - DoctorPepper)
    elif y<DoctorPepper:
        print("Not enough money")
        print ("Amount refunded")
    elif y==DoctorPepper:
        print('Here is your DoctorPepper')
elif x=='003':
    print('You have chosen Sevenup')
    y=float(input("pay the amount:\n"))
    Sevenup = 2.00
    if y > Sevenup:
        print ("Take your change with your selected item: ",y - Sevenup)
    elif y<Sevenup:
        print("Not enough money")
        print ("Amount refunded")
    elif y==Sevenup:
        print ('Here is your Sevenup')
elif x=='004':
    print('You have chosen Cola')
    y=float(input("pay the amount:\n"))
    Cola = 4.00
    if y > Cola:
        print ("Take your change with your selected item: ",y - Cola)
    elif y<Cola:
        print("Not enough money")
        print ("Amount refunded")
    elif y==Cola:
        print('Here is your Cola')
elif x=='005':
    print('You have chosen Juice')
    y=float(input("pay the amount:\n"))
    Juice = 2.50
    if y > Juice:
        print ("Take your change with your selected item: ",y - Juice)
    elif y<Juice:
        print("Not enough money")
        print ("Amount refunded")
    elif y==Juice:
        print('Here is your Juice')
elif x=='006':
    print('You have chosen Icetea')
    y=float(input("pay the amount:\n"))
    Icetea = 6.00
    if y > Icetea:
        print ("Take your change with your selected item: ",y - Icetea)
    elif y<Icetea:
        print("Not enough money")
        print ("Amount refunded")
    elif y==Icetea:
        print('Here is your CIcetea')
elif x=='007':
    print('You have chosen Water')
    y=float(input("pay the amount:\n"))
    Water = 1.00
    if y > Water:
        print ("Take your change with your selected item: ",y - Water)
    elif y<Water:
        print("Not enough money")
        print ("Amount refunded")
    elif y==Water:
        print('Here is your Water')
elif x=='008':
    print('You have chosen Miranda')
    y=float(input("pay the amount:\n"))
    Miranda = 3.00
    if y > Miranda:
        print ("Take your change with your selected item: ",y - Miranda)
    elif y<Miranda:
        print("Not enough money")
        print ("Amount refunded")
    elif y==Miranda:
        print('Here is your Miranda')
elif x=='009':
    print('You have chosen Pepsi')
    y=float(input("pay the amount:\n"))
    Pepsi = 3.00
    if y > Pepsi:
        print ("Take your change with your selected item: ",y - Pepsi)
    elif y<Pepsi:
        print("Not enough money")
        print ("Amount refunded")
    elif y==Pepsi:
        print('Here is your Pepsi')
elif x=='010':
    print('You have chosen Sprite')
    y=float(input("pay the amount:\n"))
    Sprite = 3.50
    if y > Sprite:
        print ("Take your change with your selected item: ",y - Sprite)
    elif y<Sprite:
        print("Not enough money")
        print ("Amount refunded")
    elif y==Sprite:
        print('Here is your Sprite')
while True:
    z=str(input("--------------------\nPurchase additional items yes/no:\n"))
    if z=='no':
        print("====================\nWe appreciate your use of the vending machine:\n")
        break
    elif z=='yes':
        x=str(input("Enter the code to purchase:\n"))
    if x=='001':
        print('You have chosen MountainDew')
        y=float(input("pay the amount:\n"))
        MountainDew = 3.50
        if y > MountainDew:
            print ("Take your change with your selected item: ",y - MountainDew)
        elif y<MountainDew:
            print("Not enough money")
            print ("Amount refunded")
        elif y==MountainDew:
            print('Here is your MountainDew')
    elif x=='002':
        print('You have chosen DoctorPepper')
        y=float(input("pay the amount:\n"))
        DoctorPepper = 5.00
        if y > DoctorPepper:
            print ("Take your change with your selected item: ",y - DoctorPepper)
        elif y<DoctorPepper:
            print("Not enough money")
            print ("Amount refunded")
        elif y==DoctorPepper:
            print('Here is your DoctorPepper')
    elif x=='003':
        print('You have chosen Sevenup')
        y=float(input("pay the amount:\n"))
        Sevenup = 2.00
        if y > Sevenup:
            print ("Take your change with your selected item: ",y - Sevenup)
        elif y<Sevenup:
            print("Not enough money")
            print ("Amount refunded")
        elif y==Sevenup:
            print('Here is your Sevenup')
    elif x=='004':
        print('You have chosen Cola')
        y=float(input("pay the amount:\n"))
        cola = 4.00
        if y > cola:
            print ("Take your change with your selected item: ",y - Cola)
        elif y<Cola:
            print("Not enough money")
            print ("Amount refunded")
        elif y==Cola:
            print('Here is your Cola')
    elif x=='005':
        print('You have chosen Juice')
        y=float(input("pay the amount:\n"))
        Juice = 2.50
        if y > Juice:
            print ("Take your change with your selected item: ",y - Juice)
        elif y<Juice:
            print("Not enough money")
            print ("Amount refunded")
        elif y==Juice:
            print('Here is your Juice')
    elif x=='006':
        print('You have chosen Icetea')
        y=float(input("pay the amount:\n"))
        Icetea = 6.00
        if y > Icetea:
            print ("Take your change with your selected item: ",y - Icetea)
        elif y<Icetea:
            print("Not enough money")
            print ("Amount refunded")
        elif y==Icetea:
            print('Here is your Icetea')
    elif x=='007':
        print('You have chosen Water')
        y=float(input("pay the amount:\n"))
        Water = 1
        if y > Water:
            print ("Take your change with your selected item: ",y - Water)
        elif y<Water:
            print("Not enough money")
            print ("Amount refunded")
        elif y==Water:
            print('Here is your Water')
    elif x=='008':
        print('You have chosen Miranda')
        y=float(input("pay the amount:\n"))
        Miranda =  3.00
        if y > Miranda:
            print ("Take your change with your selected item: ",y - Miranda)
        elif y<Miranda:
            print("Not enough money")
            print ("Amount refunded")
        elif y==Miranda:
            print('Here is your Miranda')
    elif x=='009':
        print('You have chosen Pepsi')
        y=float(input("pay the amount:\n"))
        Pepsi = 3.00
        if y > Pepsi:
            print ("Take your change with your selected item: ",y - Pepsi)
        elif y<Pepsi:
            print("Not enough money")
            print ("Amount refunded")
        elif y==Pepsi:
            print('Here is your Pepsi')
    elif x=='010':
        print('You have chosen Sprite')
        y=float(input("pay the amount:\n"))
        Sprite = 3.50
        if y > Sprite:
            print ("Take your change with your selected item: ",y - Sprite)
        elif y<Sprite:
            print("Not enough money")
            print ("Amount refunded")
        elif y==Sprite:
            print('Here is your Sprite')
