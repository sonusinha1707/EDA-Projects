# Hotel Booking EDA

![](https://github.com/sonusinha1707/EDA-Projects/blob/main/Hospitality_Domain_EDA_With_PowerBI_Dashboard_Project/cover.jpg)

This project analyzes hotel booking cancellations and other relevant factors that impact the business and revenue generation of City Hotel and Resort Hotel. The high cancellation rates have resulted in decreased revenue and less efficient use of hotel rooms, so lowering cancellation rates is the primary goal of both hotels to increase revenue and improve efficiency.




## Exploratory Data Analysis (EDA)

EDA is conducted to investigate and summarize key characteristics of the data to uncover patterns, relationships, and insights. The EDA in this project includes non-graphical and graphical methods, such as shape, summary, describe, isnull, info, dtypes, pie, scatter, box, bar, density, and correlation plots. The EDA covers several aspects of hotel bookings, including percentage of booking, cancelled bookings, length of stay, parking space, preferred meal type, lead time, room type, busiest month, ADR, guest type, origin of guests, agent, and distribution channel and market segment.
### Key Features

## Problem Statement

This hotel booking dataset can help us explore various questions related to booking cancellations, increasing revenue, improving efficiency, and identifying the busiest periods in the hotel industry. The dataset contains booking information for city hotels and resort hotels, including details such as:

- When the booking was made
- Length of stay
- Number of adults, children, and/or babies
- Number of available parking spaces

The aim of this project is to analyze this data and derive insights that can help improve business operations and customer satisfaction.

## Tools and Libraries Used

This project utilizes the following Python libraries:

- `pandas` for data manipulation
- `numpy` for numerical operations
- `seaborn` and `matplotlib` for visualizations
- `plotly.express` for interactive plotting
- `folium` for map visualizations
- `datetime` for handling date and time data
- `pycountry` for country-related data
- `warnings` to suppress unnecessary warnings

## Key Features

- **Data Cleaning and Preprocessing:** Ensured the data is ready for analysis by handling missing values, encoding categorical variables, and transforming columns.
- **Exploratory Data Analysis (EDA):** Explored patterns in booking trends, seasonality, customer segmentation, and cancellations.
- **Visualization:** Used advanced visualization techniques to identify key insights and present them effectively.
- **Interactive Analysis:** Created dashboards using Plotly for real-time insights.

## Project Structure

1. **Data Loading and Overview:** Initial data exploration, including loading and cleaning.
2. **Feature Engineering:** Creation of new meaningful variables.
3. **EDA:** Visualization and analysis of key trends.
4. **Insights:** Business recommendations based on analysis.

**Percentage of booking in each hotel:**

Using the help of pie chart and bar plot, it has been found that the percentage of booking in the City Hotel is 1.57 times more as compared to that in the Resort Hotel. People usually book a city hotel for business or short trip while Resort hotels are mostly known for spending holidays.

**Cancelled bookings:**

As revealed earlier that the City Hotel has a higher number of bookings compared to the Resort Hotel, the City Hotel also experiences a higher percentage of cancellations than the Resort Hotel. Maximum number of cancellations are seen during summer. There may be a number of factors contributing to this cancellation.

**Length of stay:**

It is seen that people usually stay for less than 7 days in either of the hotels. Guests usually stay for small duration in City Hotel, while for longer duration they prefer Resort Hotel.

**Parking space:**

The pie charts indicates that most customers in both City and Resort hotels do not need parking. However, the Resort hotel has a higher percentage of customers who require parking than the City hotel. Therefore, it is important for Resort hotels to provide at least one parking space per reservation to meet their customers' needs.

**Preferred meal type:**

The Bed and Breakfast (BB) plan is the most popular meal plan in both hotels. The Half Board (HB) plan is more popular at the Resort Hotel as compared to at the City Hotel. The very low number of meals served under the FB plan at both the hotels suggests that this may not be a popular option for guests.

**Lead time:**

The data shows that as lead time increases, the number of cancellations in hotel bookings also tends to increase. To meet the needs of customers, it is crucial to provide accurate, real-time information and offer flexible booking options that allow for easy modifications.

**Room type:**

The room type with the most number of bookings is A followed by D. Adults usually prefer room of type A, D and G with increasing number of guests. While parents usually book room B for their children.

**Busiest month:**

Both these hotels enjoy a good number of guests during the spring and summer seasons. However, this number decreases once autumn kicks in and the number goes on decreasing till winter.

**ADR:**

During the busier seasons, ADR seems to be on the higher side. As ADR increases, number of cancellations also increases. This can be due the fact that guests often book a hotel but at the time of checking in they seem reluctant to pay such a high price and look for alternative hotels.

**Guest type:**

Most of the guests are of transient type and there is anoticeable surge in the number from June to August. While other types of guests have a few visits as compared to that of transient ones.

**Origin of guests:**

Most of the guests are from Portugal followed by UK, France, Spain and Germany.

**Agent:**

Maximum number of bookings were made by the agent with ID=9 followed by 240, 7, 14 and 250.

**Distribution channel and market segment:**

The majority of bookings at the hotels come from guests in the Online/Offline Travel Agency distribution channel, followed by those in the Direct channel. The majority of bookings at the hotels come from guests in the Online Travel Agency market segment, followed by those in the Offline Travel Agency market segment.

## Power BI Dashboard

![](https://github.com/sonusinha1707/EDA-Projects/blob/main/Hospitality_Domain_EDA_With_PowerBI_Dashboard_Project/Dashboard.png)

## Key Insights

1. **Peak Booking Periods**
   - **Insight:** The busiest booking periods are during summer (June to August) and year-end holidays (December). This trend highlights seasonal peaks in both city and resort hotels.
   - **Actionable Recommendation:** Increase staffing and promotional offers during these peak months to capitalize on demand and ensure smooth operations.

2. **Booking Cancellations**
   - **Insight:** Over 20% of total bookings are canceled. Higher cancellation rates are observed for bookings made with longer lead times.
   - **Actionable Recommendation:** Implement flexible cancellation policies or incentives (e.g., discounts for non-refundable bookings) to reduce cancellations.

3. **Customer Segments**
   - **Insight:** Families and groups tend to prefer resort hotels, while solo travelers and business clients mostly choose city hotels.
   - **Actionable Recommendation:** Tailor marketing campaigns to target families for resorts and professionals for city hotels to maximize bookings.

4. **Revenue Impact of Length of Stay**
   - **Insight:** Guests staying longer than 3 nights contribute disproportionately to revenue, especially at resort hotels.
   - **Actionable Recommendation:** Offer package deals for extended stays to encourage longer bookings, boosting revenue.

5. **Geographical Trends**
   - **Insight:** Most international guests come from a few key countries, such as Portugal, the UK, and France. However, there is untapped potential in emerging markets.
   - **Actionable Recommendation:** Develop partnerships and targeted marketing campaigns in these high-potential regions to attract more international guests.


## Recommendations

1. Guest surveys can be used to create a dataset to identify reasons and demographics behind the cancellations, and to develop targeted actions and a machine learning model to forecast cancellations. Such measures can help improve the booking retention rates and overall financial performance of the hotels.
2. Attracting Contract and Group guests can diversify the guest mix. Offering yearly subscriptions and unique benefits can be effective strategies to differentiate them from Transient and Transient-Party guests.
3. Before converting low-demand room types to high-demand ones, it's essential to consider customer preferences and unique features. Instead, other strategies such as pricing or marketing may be more effective in increasing demand.
4. The logistic team at the resort hotel should be mindful that around 20% of guests will likely need at least one parking space, and ensure there are enough spots to accommodate all cars.
5. Higher ADR is linked to increased cancellation rates, potentially due to factors like cost, travel plans, or negative reviews. Hotel operators should strive to find a balance between pricing and guest satisfaction to maximize revenue and reputation.
6. Long lead times are linked to high cancellation rates. To reduce cancellations, hotels can implement strategies such as flexible cancellation policies, promoting direct bookings, dynamic pricing, and targeted last-minute marketing campaigns.
## Conclusion

EDA is essential for data analysis as it provides valuable insights by examining distributions, relationships, and trends in the data. The EDA in this project sheds light on several aspects of hotel bookings and provides recommendations to improve the business and revenue generation of City Hotel and Resort Hotel.
