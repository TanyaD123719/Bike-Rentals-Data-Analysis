This project explores a real-world dataset to understand how environmental and temporal factors affect bike rental patterns. The dataset includes variables such as rental volume, month, season, holidays, and weather-related metrics including temperature, humidity, visibility, UV index, wind speed, rainfall, and snowfall.

Using Python and libraries like pandas, seaborn, and matplotlib, the analysis involved filtering data based on user input (month and season), creating visualizations, and interpreting trends using regression plots. The aim was to identify patterns and generate actionable insights for improving bike-sharing operations and planning.

🔍 Key Insights:
Rainfall and Snowfall: Even minor precipitation causes a sharp decline in rentals. This confirms that adverse weather significantly deters ridership, primarily due to safety and comfort concerns.

UV Index: Rentals increase with moderate UV exposure, indicating sunny weather encourages usage. However, very high UV levels slightly reduce rentals, likely due to discomfort from heat.

Wind Speed: A negative correlation exists between wind speed and rentals. High wind appears to discourage bike use, emphasizing the impact of wind on outdoor mobility choices.

Visibility: Clearer conditions (higher visibility) correspond with increased rentals, suggesting that good visibility improves perceived safety and comfort.

Holidays: Rental volume consistently drops on holidays, supporting the idea that bikes are used more for commuting than for recreational travel.

🧰 Tools & Techniques:
Data filtering using pandas

Scatter plots and trend lines via seaborn and matplotlib

Conditional user inputs to simulate real-world interaction

Regression analysis for pattern recognition

This analysis highlights how weather and time-based factors directly influence user behavior in bike-sharing systems. It supports the implementation of dynamic operations—like real-time fleet rebalancing, weather-based promotions, and targeted communication strategies—to enhance service delivery and user satisfaction.
