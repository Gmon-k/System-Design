# System-Design
UML 1
I have created a system diesign for  with a small software company, developing a new frequent flyer management system (similar to, for example, Alaska Airlines or Delta apps). team is developing an part of a system that would allow a user to see their current miles balance, and use their miles.
For now, your frequent flyer app consists of:
• Frequent Flyer. A frequent flyer is an individual with:
o AuniqueaccountID,whichisa12-characterlongString. o Aname,consistingoffirst,middleandlastname.
o Anemailaddress,and
o Amilesbalance.
• Miles Balance is an object consisting of:
o Anintegervalue,representingtotalmilesavailable,
o Anintegervalue,representingmilesearnedthisyear,


UML 2
vehicle valuation company, similar to Kelley Blue Book. the company is developing a next generation of the vehicle management system. At this stage, however, the company just wants to build a simple system, to store the needed information about vehicles.
So, currently, your system distinguishes between two major kinds of vehicles: 
• Cars
• Vessels
A car can be one of:
• Used car
• New car
The only vessel that your system currently recognizes is a Boat. For every vehicle, your system keeps track of the following:
• ID, a unique identifier of a vehicle, represented as a String
• Manufacturing year, a year vehicle was manufactured, represented as an Integer
• Make and model, represented as a MakeModel, a custom class that you will have to develop, and that keeps track of:
o Make, vehicle make, represented as a String o Model, vehicle model, represented as a String
• MSRP, Manufacturer Suggested Retail Price, represented as a Double.
For every new car, the system additionally keeps track of number of available vehicles within 50
miles, represented as an Integer.
For every used car, the system keeps track of:
• Mileage, represented as an Integer
• Number of previous owners, represented as an Integer
• Number of minor traffic accidents the vehicle was involved in, represented as
an Integer
Lastly, for every boat, the system additionally keeps track of:
• Length, boat length, represented as a Float
• Number of passengers, represented as an Integer
• Propulsion type, represented as an PropulsionType, a custom enumeration that you will have to develop, with possible value: Sail Power, Inboard Engine, Outboard Engine, Jet Propulsion.


UML 3
system deisgn for developing a new interactive tax return preparation system, similar to TurboTax or QuickBooks. Your system is intended to help tax filers fill and submit their tax return forms, but for now, your team is focused on building a simple proof-of-concept tax calculator.
The tax calculator distinguishes between two kinds of tax filers:
• Individual filers
• Group filers
Individual filer can be one of:
• Employee
Group filer can be one of:
• Married, filling jointly
• Married, filling separately
• Head of the household
For every tax filer, your system keeps track of the following:
• Tax ID, a unique tax filer’s identifier, represented as a String.
• Contact info, represented as a ContactInfo, a custom class that you will have to
develop, and that keeps track of:
• Name, a tax filer’s first and last name, represented as a Name, another custom
class that you will have to develop,
• Address, a tax filer’s address, represented as a String,
• Phone number, the tax filer’s phone number, represented as a String,
• Email address, the tax filer’s email address, represented as a String.
• Last year’s earnings, represented as a Double.
• Total income tax already paid, represented as a Double.
• Mortgage interest paid, represented as a Double.
• Property taxes paid, represented as a Double.
• Student loan and tuition paid, represented as a Double.
• Contributions made to a retirement savings account, represented as a Double.
• Contributions made to a health savings account, represented as a Double.
• Charitable donations and contributions, represented as a Double.
For every group filer, the tax calculator keeps track of:
• Number of dependents, represented as an Integer.
• Number of minor children, represented as an Integer.
• Childcare expenses, represented as a Double.
• Dependent-care expenses, represented as a Double.
