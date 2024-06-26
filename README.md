 
Car Sales Segmentation Project
This project analyzes car sales data to segment customers based on their preferences, brand loyalty, and price sensitivity using clustering techniques. It includes feature selection, principal component analysis (PCA), logistic regression for feature importance, and K-means clustering. The segments identified can help in targeted marketing strategies and understanding customer behavior.
Project Structure
•	Data:
o	The project uses a CSV file Car_Sales.csv containing car sales data, including attributes like Annual Income, Price, Body Style, Engine, Transmission, and Color.
•	Code Files:
o	car_sales_segmentation.ipynb: Jupyter Notebook containing Python code for data preprocessing, feature selection, PCA, clustering, and visualization.
•	Output:
o	output_segmentation.csv: CSV file containing segmentation results with columns for Car ID, Customer Name, Gender, and Cluster labels for Car Preference, Brand Loyalty, and Price Sensitivity.
•	Visualizations:
o	The Notebook includes various plots:
	Elbow method and silhouette scores for determining optimal clusters.
	Heatmaps and bar plots for visualizing correlations and average feature values across clusters.
Key Components
Data Preprocessing
•	Missing values in selected features (Initial Features) are handled by dropping rows with missing data.
•	Categorical variables (Body Style, Engine, Transmission, Color) are encoded using numeric codes.
Feature Selection and PCA
•	Logistic Regression is used to select top features based on importance.
•	Principal Component Analysis (PCA) is performed to reduce dimensionality while preserving variance.
Clustering
•	K-means clustering is applied to identify segments:
o	Car Preference: Clusters based on Body Style, Price, and Annual Income.
o	Brand Loyalty: Clusters based on Annual Income, Engine, and Transmission.
o	Price Sensitivity: Clusters based on Price and Annual Income.
Visualizations
•	Elbow method and silhouette scores plots aid in determining the optimal number of clusters.
Output
•	The final segmentation results are saved in output_segmentation.csv, detailing customer segments for Car Preference, Brand Loyalty, and Price Sensitivity.
Car Preference Segments:
Cluster 0: Luxury car buyers
Cluster 1: Economy car buyers
Cluster 2: SUV enthusiasts
Cluster 3: Passenger car preference

Brand Loyalty Segments:
Cluster 0: Domestic brand loyalists
Cluster 1: Import brand enthusiasts

Price Sensitivity Segments:
Cluster 0: Budget-conscious
Cluster 1: Mid-range buyers


Leveraging customer segmentation can significantly enhance sales and marketing efforts.
Marketing Strategies for Each Segment:
1. Car Preference Segments:
•	Luxury Car Buyers:
o	Strategy: Highlight premium features, exclusive services, and high-end brand values.
o	Channels: Use luxury magazines, exclusive events, and personalized email campaigns.
o	Offers: Provide VIP services, exclusive test drives, and loyalty rewards.
•	Economy Car Buyers:
o	Strategy: Focus on affordability, fuel efficiency, and reliability.
o	Channels: Utilize social media, budget-conscious advertising, and price comparison websites.
o	Offers: Emphasize discounts, financing options, and trade-in deals.
•	SUV Enthusiasts:
o	Strategy: Promote the versatility, safety features, and spaciousness of SUVs.
o	Channels: Leverage outdoor and adventure-related media, family-focused advertising.
o	Offers: Highlight family packages, off-road capabilities, and safety ratings.
•	Passenger Car Preferrers:
o	Strategy: Emphasize the practicality, comfort, and efficiency of passenger cars.
o	Channels: Use urban and lifestyle media, public transportation hubs.
o	Offers: Focus on urban driving features, carpool incentives, and eco-friendly options.
2. Brand Loyalty Segments:
•	Domestic Brand Loyalists:
o	Strategy: Reinforce national pride, reliability, and community support associated with domestic brands.
o	Channels: Use local media, community events, and sponsorships.
o	Offers: Provide loyalty programs, trade-in bonuses, and community discounts.
•	Import Brand Enthusiasts:
o	Strategy: Highlight the innovation, performance, and design of imported brands.
o	Channels: Leverage global media, digital advertising, and influencer partnerships.
o	Offers: Offer international warranties, tech upgrades, and performance packages.
3. Price Sensitivity Segments:
•	Budget-Conscious Buyers:
o	Strategy: Focus on value for money, long-term savings, and essential features.
o	Channels: Use discount channels, budget forums, and social media groups.
o	Offers: Provide clear pricing, extended warranties, and fuel-efficient models.
•	Mid-Range Buyers:
o	Strategy: Balance quality with affordability, highlighting the best value propositions.
o	Channels: Utilize mainstream media, email marketing, and comparison tools.
o	Offers: Offer mid-tier packages, financing options, and feature upgrades.
•	Premium Buyers:
o	Strategy: Emphasize exclusivity, advanced technology, and superior service.
o	Channels: Use premium channels, luxury events, and personalized outreach.
o	Offers: Provide bespoke services, luxury add-ons, and premium financing plans.




