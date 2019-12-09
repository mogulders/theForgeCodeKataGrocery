# theForgeCodeKataGrocery


TheForgeCodeKataGrocery
This is a kata for the checkout order total kata. 

Dependencies:

I only have one dependency and it’s for reading in excel file information.
pip install xlrd

Running the tests:

I have included an if name == main statement in my test code so that I could run my tests in my IDE. 
Deployment
Add additional notes about how to deploy this on a live system

Pros
1. Specialties are Dynamic. Adding more specialties to the system will be easy as the specialty is all called and checked in one spot. 
2. Item lists are populated easily.
3. Excel file is uniform/quick/easy to use. With the excel file employees of said grocery store will be able to easily make changes on their end without any hassle. The excel file is uniform, quick, and easy to use. Making the inventory data concise and readable.

Cons
1. Must entirely remove lb objects instead of subtracting. All lb objects if you were to over-ring how many pounds you wanted must be entirely removed and then the correct amount added back in.
2. Limits must be manually calculated right now. Since my program functions on limits and specialty variables a limit of 3 in a buy 3 for 10 situation actually means the limit in the cart is 9 and all of that must be manually calculated right now. 
3. Specialty Variables while functional can be confusing at times. While the specialty variables are functional they can get confusing at times.
4. Naming/entering names is sensitive with likely many items that are hard to spell. When adding items to the cart it can get touchy especially since I took the naming route of NO PLURALS. So adding grape instead of grapes(which sometimes seems counterintuitive).
5. The decimals in the specialty cases. There are some unique cases when adding decimals of lb objects where the price carries out to some odd decimal place. Right now this is no problem as it doesn’t affect the price output or price to two decimals, but could be an issue down the road.

Authors
•	Jacob Zanders
