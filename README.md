# bmi_python

Calculate bmi index for you and help you with your status.

def say_bmi():
    height = input("How Tall are you in cm :")
    weight = input(" how much is your weight :")
    bmi = int (weight)/(int(height)/100)**2
    print ( "Your BMi index is " , + round(bmi,2))
    if bmi < 18.5:
      print ("You bette have good diet")
    elif bmi >= 18.5 and bmi <= 24:
      print ("Keep up Good Health")
    else:
        print("You Better take care and do exercise")    
