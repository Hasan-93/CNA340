# Automobile service invoice

In this lab we will write a Program for Automobile service invoice to
output a menu of automotive services and the corresponding cost of each service and service are
Oil change -- $35
Tire rotation -- $19
Car wash -- $7
Car wax -- $12
and we need to prompt the user for two services from the menu.

## Getting Started

Output a menu of automotive services and the corresponding cost of each service.
Davy's auto shop services
Oil change -- $35
Tire rotation -- $19
Car wash -- $7
Car wax -- $12

Prompt the user for two services from the menu.
Select first service:
Oil change
Select second service:
Car wax


Output an invoice for the services selected. Output the cost for each service and the total cost
Davy's auto shop invoice

Service 1: Oil change, $35
Service 2: Car wax, $12

Total: $47

Extend the program to allow the user to enter a dash (-), which indicates no service. 

Davy's auto shop services
Oil change -- $35
Tire rotation -- $19
Car wash -- $7
Car wax -- $12

Select first service:
Tire rotation
Select second service:
-

Davy's auto shop invoice

Service 1: Tire rotation, $19
Service 2: No service

Total: $19

### Prerequisites

Automobile service invoice requires PyCharm ,Version: 2020.1.1to run, with Community Edition packages. The commands below will help finish the Programing for Automobile service.

```
#Output a menu of automotive services and the corresponding cost of each service.
print("Davy's auto shop services")
print("Oil change -- $35")
print("Tire rotation -- $19")
print("Car wash -- $7")
print("Car wax -- $12")

#Prompt the user for two services from the menu.
shopService1=input("\nSelect first service:\n")                 # Oil change
shopService2=input("Select second service:\n")                  # Car wax
totalServiceAmount=0                                            # Service total
print("\nDavy's auto shop invoice\n")                           # print invoice


#Output an invoice for the services selected. Output the cost for each service and the total cost
#(Service 1)

if(shopService1.lower()=="oil change"):
    print("Service 1: Oil change, $35")                         # Line 17 to 19 for Oil change
    totalServiceAmount=totalServiceAmount+35 
    
    
elif(shopService1.lower()=="tire rotation"):
    print("Service 1: Tire rotation, $19")                      #line 22 to 24 for Tire rotation
    totalServiceAmount=totalServiceAmount+19 
    
    
elif(shopService1.lower()=="car wash"):
    print("Service 1: Car Wash, $7")                            #line 27 to 29 for Car wash
    totalServiceAmount=totalServiceAmount+7 
    
    
elif(shopService1.lower()=="car wax"):
    print("Service 1: Car Wax, $12")                            #Line 32 to 34 for Car wax
    totalServiceAmount=totalServiceAmount+12 
    
    
elif(shopService1=="-"):                                        #Line 38 to 39 For No service
    print("Service 1: No service")
    
#Output an invoice for the services selected. Output the cost for each service and the total cost
#(Service 2)    

if(shopService2.lower()=="oil change"):
    print("Service 2 Oil change, $35")                          # Line 44 to 46 for Oil change
    totalServiceAmount=totalServiceAmount+35 
    
    
elif(shopService2.lower()=="tire rotation"):
    print("Service 2: Tire rotation, $19")                      # Line 49 to 51 for Tire rotation
    totalServiceAmount=totalServiceAmount+19 
    
    
elif(shopService2.lower()=="car wash"):
    print("Service 2: Car wash, $7")                            # Line 54 to 56 for Car wash
    totalServiceAmount=totalServiceAmount+7 
    
    
elif(shopService2.lower()=="car wax"):
    print("Service 2: Car wax, $12")                            # Line 59 to 60 for Car wax
    totalServiceAmount=totalServiceAmount+12 
    
    
elif(shopService2=="-"):                                        # Line 64 to 65 for No service
    print("Service 2: No service")
    
    

print("\nTotal: $%d"%totalServiceAmount)
```

## Running
Once installed you can run the program with the following command

```
Oil change
Car wax
Tire rotation
Car wash
Tire rotation
-
-
Car wax
```

Add any additional ways to run the program below

```
Tire rotation
-
-
Car wax
```

## Thanks
Thank you for joining my Automobile service invoice Py programing.
