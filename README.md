# NYC TLC Trip Record - Green Taxi Analysis

## 1. Overview

The New York City Taxi & Limousine Commission (NYC TLC) is responsible for regulating, licensing, and overseeing transportation services, including Yellow Taxi, Green Taxi, For-Hire Vehicles (FHV), Commuter Vans, and Paratransit Vehicles. Green Taxi was introduced by NYC TLC in 2013 to serve Upper Manhattan and areas outside Manhattan. Green Taxis can be owned by individuals, taxi companies, or local entrepreneurs.

The main challenges faced by Green Taxi fleet owners are competition from Yellow Taxis and FHV services such as Uber and Lyft. With technological advancements, another challenge is the shift toward online and app based booking systems. Green Taxi services are now available through the official NYC TLC app as well as third-party applications. However, further performance improvements are needed to maintain and increase customer trust so that they continue to choose Green Taxi services.

Based on these issues, this analysis aims to address the following objectives:

- Identify high-demand locations based on regions and zones
- Identify peak demand times based on dates, days, and hours
- Analyze customer preferences and behavior based on payment methods, tipping patterns, and taxi usage

## 2. Data

The dataset used in this analysis was obtained from the official NYC TLC website. ([NYC TLC Official Site](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page))

Datasets:
- NYC TLC Trip Record.csv
- taxi_zone_lookup.csv

Analysis Files:
- Green Taxi Analysis by yanfa121.ipynb (Jupyter Notebook)
- Green Taxi Analysis Presentation.pdf (Presentation Draft)
- Green Taxi Dashboard.twb [(Tableau Public Link)](https://public.tableau.com/views/GreenTaxiDashboard_17555258827810/NYC?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
- NYC TLC Trip Record.csv (Raw Data)
- NYC TLC Trip Record CLEAN.csv (Cleaned Data)
- taxi_zone_lookup.csv (Additional Data)

## 3. Tools Used

Microsoft Visual Studio Code, Jupyter Notebook

Programming Language : Python (Pandas, NumPy, SciPy)

Visualization : Seaborn, Matplotlib

Interactive Dashboard : Tableau

Presentation : Canva

## 4. Conclusions and Recommendations
### Conclusions

Based on the analysis, the following insights were obtained :
- Manhattan has the highest demand, followed by Queens and Brooklyn
- The highest demand zones are located in Manhattan
- Weekdays generate higher demand than weekends, except in Brooklyn, where demand is higher on weekends
- On public holidays, demand tends to decrease due to lower community mobility
- Peak demand occurs during rush hours:
  - Morning: 7:00 – 9:00
  - Midday: 10:00 – 14:00
  - Afternoon: 15:00 – 18:00
- Most customers prefer credit card payments
- Many customers use taxis for short distance trips (< 5 miles)
- Tips have a positive correlation with total trip cost, although the correlation strength is moderate
- There are other factors beyond trip cost that influence tipping behavior
- Tip amounts vary across different regions

### Recommendations

Several strategies can be implemented :
- Optimize fleet allocation in Manhattan, especially during peak hours, by reallocating vehicles from low demand zones to high demand zones
- Focus fleet operations in Brooklyn on weekends by shifting vehicles from less busy zones in other regions
- Reduce the number of active vehicles on public holidays to improve operational efficiency
- Ensure responsive fleet availability during peak hours to maintain adequate supply
- Since credit card usage is dominant, collaborate with credit card providers to offer promotions such as cashback or reward points
- Implement flat fares for trips under 5 miles to enhance customer value and loyalty
- Strengthen services in the Central Business District (Manhattan), considering the high demand for short distance trips
- Conduct customer satisfaction surveys for continuous evaluation
- Improve driver friendliness and vehicle cleanliness to enhance customer comfort and satisfaction
- Optimize service strategies for each region; for example, in Manhattan, focus not only on tips but also on leveraging high trip volumes

## 5. Contact

Yanfa Anandika

📧 Email : yanfaanandika21@gmail.com

🔗 LinkedIn : [Yanfa Anandika](https://www.linkedin.com/in/yanfa-anandika-a663bb170/)

💻 GitHub : [yanfa121](https://github.com/yanfa121)
