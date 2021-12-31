# sofia-rachel
Contact book 
Worddic={}
Ch='y':
While ch is'y':
  Print("1.insert new phone no.") 
  Print("2.search Name")
  X=int(input("enter your choice "))
  if x is 1:
     word=input("enter the phone number :").lower()
     meaning=input("enter the name :").lower()
     insertrecord(worddic,word,meaning)

  elif x is 2:
     if len(worddic)>0:
        Word=input("enter the phone number ").lower()
        searchmeaning(worddic,word)
     else:
       Print("is empty")
  else:
    Print("invalid choice")

  Ch=input("do you want to continue (v/n)")

Print("Thank you")
  
