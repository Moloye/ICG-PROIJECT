START PROMPT items
 GET ItemName ItemName=INPUT("Item name:Shampoo, Bangs, Fringes") 
IF ItemName=("Shampoo") THEN DISPLAY("You have selected Shampoo, it costs NS500") ELSE 
IF ItemName=("Bangs") THEN DISPLAY("You have selected Bangs, it costs NS700") ELSE 
IF ItemName=("Fringes") THEN DISPLAY("You have selected Fringes, it costs NS100") ELSE
DISPLAY("This Item doesn't exist!")
 ENDIF 
ENDIF 
ENDIF 
END

PROMPT payment 
GET payment

payment=INPUT("How do you want to pay?:Credit Card, Cash") IF payment= Credit card THEN 
DISPLAY("Enter your Credit card number") ELSE
 DISPLAY (Please feel free to reach our distributors Dischem Pharmacies Namibia and PnP Namibia stores")
 ENDIF
 END

PROMPT Credit_Card_number 
GET Credit_Card_number, Amount
 DISPLAY("Thanks, enter your Amount") GET Amount IF Amount=INT(500) DISPLAY("You have bought Shampoo, enter your Home address") ELSE IF Amount=INT(700) DISPLAY("You have bought Bangs, enter your Home address") ELSE IF Amount=INT(500) DISPLAY("You have bought Fringes")

ENDIF
ENDIF
ENDIF
END

INPUT ("your Home address")
 GET address DISPLAY ("Thanks for trusting us, your item will be delivered by tomorrow")



START

PROMPT sellingPrice,costPrice 
GET sellingPrice, costPrice

sellingPrice = Buying_Price+ VAT VAT = sellingPrice - costPrice

IF sellingPrice <= costPrice THEN PRINT("Loss was made") ELSE 
IF sellingPrice => costPrice THEN

 PRINT("You gain VAT")
ENDIF ENDIF END

#Desk check for answer accepted 

sellingPrice = 500 costPrice = 300 VAT = 200

Financial return percentage = 166% expect output

START

Prompt for sellingPrice, cost_price,VAT READ sellingPrice = 500,costPrice = 300

sellingPrice = 300+200 
IF sellingPrice <= 300 THEN PRINT("Loss was made") ELSE 
IF sellingPrice => 300 THEN

PRINT("You gain N$200")
Financial return percentage = N$ 500 ÷ N$ 300 × 100 
End if 
Display financial PRINT ("percentage=166%) 
END

GET ItemName=array(Shampoo, ),(Fringes),(Bangs)

DOWHILE( ItemName=0to2)

IF products are >= 35 THEN

Execute'PRODUCT SHOULD BE TRANSPORTED TO DESTINATION' ELSE 
Execute 'THE AMOUNT OF PRODUCT YOU SELECTED DOES NOT MEET THE MINIMUM VALUE,PLEASE WAIT TILL IT DOES' ELSE 
Execute'ERROR,PLEASE TRY AGAIN LATER' 
ENDIF 
STOP

Write a program to calculate the store values and include the VAT 
START 
Enter num For e = 1 to num 
DO Enter item(e) 
Enter price 
Enter Bprice 
Enter code IF code = 1 THEN Sprice(e)= Bprice * 2.00 * 1.05 ELSE 
Sprice(e)= Bprice * 1.00 
endif 
ENDFOR 
For e = 1 to num 
DO Print item(e) 
ENDFOR 
STOP

   
   



