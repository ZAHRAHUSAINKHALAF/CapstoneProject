# Under the Hood: Analyzing Germany’s Used Car Trends!
## INTRODUCTION
With the rising demand for affordable and diverse vehicle options, used cars have become an attractive choice for buyers. As a consulting firm specializing in the used car market, we analyzed eBay’s used car listings to identify key trends and provide data-driven insights. This analysis aims to support smarter decisions for both everyday customers and automotive investors.

## PROBLEM STATEMENT
To recommend the most valuable used car options to our customers, we need to conduct a comprehensive comparison across the entire German eBay used car marketplace. Our goal is to answer key questions such as: What is a fair price range for different vehicle types? Which brands offer the best reliability, and which ones should be approached with caution? And ultimately, what kinds of cars demonstrate the highest durability over time?

## OBJECTIVES
🚙	Compare car prices by year, type, and condition.

🚙	Identify brands with extreme prices and damage rates.

🚙 Explore how mileage affects damage and price.

🚙	Analyze brand availability and their condition.

🚙	Assess listing speed and vehicle age trends.

## TARGET AUDIENCE
🚙 Costumers looking to buy used cars.

🚙	Automotive Investors.

## DATASET
The analysis utilizes the autos.csv dataset, a comprehensive web-scraped collection from the German eBay Kleinanzeigen marketplace. This dataset contains approximately 370,000 rows and 20 columns, offering rich insights into the used car market in Germany. Each entry represents a single vehicle advertisement and includes detailed features about the vehicle’s condition, pricing, listing behavior, and seller characteristics.

Dataset Links : Used Cars, Used Cars Data - dataset by data-society | data.world
While the original dataset is widely referenced in data science practice projects (such as on Kaggle or Dataquest), you may find similar versions through open-source platforms. If you'd like, I can help you locate a publicly available version.
The data dictionary :
| Column Name            | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| dateCrawled            | Date the car was crawled. (Date)                                            |
| name                   | Name of the car. (String)                                                   |
| seller                 | Type of seller (private or dealer). (String)                                |
| offerType              | Type of offer (e.g. sale, repair, etc.). (String)                           |
| price                  | Price of the car. (Integer)                                                 |
| abtest                 | Test type (A or B). (String)                                                |
| vehicleType            | Type of vehicle (e.g. SUV, sedan, etc.). (String)                           |
| yearOfRegistration     | Year the car was registered. (Integer)                                      |
| gearbox                | Type of gearbox (manual or automatic). (String)                             |
| powerPS                | Power of the car in PS. (Integer)                                           |
| model                  | Model of the car. (String)                                                  |
| kilometer              | Kilometers the car has been driven. (Integer)                               |
| monthOfRegistration    | Month the car was registered. (Integer)                                     |
| fuelType               | Type of fuel (e.g. diesel, petrol, etc.). (String)                          |
| brand                  | Brand of the car. (String)                                                  |
| notRepairedDamage      | Whether or not the car has any damage that has not been repaired. (String) |
| dateCreated            | Date the car was created. (Date)                                            |
| nrOfPictures           | Number of pictures of the car. (Integer)                                    |
| postalCode             | Postal code of the car. (Integer)                                           |
| lastSeen               | Date the car was last seen. (Date)                                          |

