# Ontology for Dairy Production

## Description
This ontology represents the structure of a dairy production system. It includes dairy farm, cattle, milk production, feed, processing, supply chain classes.

## Classes 
Below is an explanation of every declared class:
- **DairyFarm**: Represents a dairy farm. 
- **Cattle**: Represents cows. Has subclasses such as: Age, Breed and Health status.
- **Milk**: Represents produced milk. 
- **Feed**: Represents different types of cattle feed. 
- **Processing**: Represents milk processing stages with subclasses like Pasteurization, Homogenization, Cheese making, Yogurt production.
- **SupplyChain**: Represents the distribution system which devided to Packaging, Transportation, Retailstores subclasses.
- **DairyProducts**:  Represents the produced products.

## Object Properties
- **hasCattle**: Means Dairy farm has cattle.
- **producesMilk**: Means Cattle produce milk.
- **consumesFeed**: Means Cattle consume feed.
- **isProcessedInto**: Means Milk is processed into dairy products.
- **delivering**: Means Dairy products delivery.
- **produces**: Means Dairy farm produce dairy products.

## Data Properties
- **destination**:   
Domain: RetailStores  
Range: xsd:string  
A simple data property that stores the textual name of the retail stores.
- **expirationDate**:  
Domain: DairyProducts  
Range: xsd:dateTime  
A simple data property that stores the expiration date of products.
- **transportationDate**:  
Domain: Transportation  
Range: xsd:dateTime  
A simple data property that stores the transportation date.



Graphical view of ontology: 
![image](https://github.com/user-attachments/assets/e5a5242d-7104-4d19-8004-d8f3d8bee9db)




