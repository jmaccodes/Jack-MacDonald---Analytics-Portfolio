# Analytics Projects

# [Project 1: Credit Card Default Predictive Model](https://github.com/jmaccodes/Predictive-Modeling---Python)

This project analyzes customer credit card data to identify key variables that impact the likelihood of defaulting on credit card payments. It uses both logistic regression and a categorical decision tree model to provide insights into credit risk and help develop strategies for risk mitigation.

- Objective: Determine which factors influence the probability of credit card default using 
  statistical and machine learning models.
- Dataset: Customer credit card data containing demographic, financial, and behavioral variables.
- Methodology: Logistic regression for binary classification and statistical interpretation.
  Categorical decision tree for interpretable machine learning and visualization of decision paths.
- Key Deliverables: Trained logistic regression and decision tree models.
- Insights into significant predictors of credit default risk.
  Recommendations for risk mitigation strategies.

# [Project 2: Data Mangement SQL - Final Project](https://github.com/jmaccodes/Data-Management---Final-Project-SQL-)

This project analyzes a video rental store database to extract insights on film inventory, customer behavior, rental transactions, and pricing strategies. It uses SQL queries to support business decisions related to marketing campaigns, inventory management, and revenue optimization.

- Objective: Analyze rental patterns, film popularity, and customer behavior using SQL queries.  
- Dataset: A relational database containing tables for films, rentals, customers, actors, and transactions.  
- Methodology:  
  - SQL queries for data retrieval, filtering, and aggregation.  
  - Joins to connect multiple tables and extract business insights.  
  - Case statements and categorization for enhanced analysis.  
- Key Deliverables:  
  - Insights into film inventory and rental trends.  
  - Identification of top-performing films and actors.  
  - Evaluation of pricing structures and customer engagement.

# [Project 3: API Pull Request - Crunchbase API](https://github.com/jmaccodes/API-Data-Extract)

 This project utilizes Python to build functions to pull private company financial information from the Crunchbase API Trial Key

- Objective: Source financial data on private companies.
- Methodology:
   
API Request & Data Retrieval (GetOrgCards)
  - API Integration, HTTP GET Requests
  - The function constructs an API URL to query Crunchbase's database for organization-related data.
  - Uses the requests library to send a GET request with an API key in the headers.
  - Handles HTTP responses, checking if the request was successful (status_code == 200).
  - Extracts JSON data from the response and normalizes it using Pandas' json_normalize().

JSON Parsing & Data Structuring (parse_api_json)
  - Parses the JSON response into a structured Pandas DataFrame.
  - Extracts key fields from the JSON response (company name, funding, LinkedIn, etc.).
  - Handles missing data using .get() with default values.

# [Project 4: Streamlit - Ebay Data Visualization](https://github.com/jmaccodes/Streamlit_Data_Viz)

This interactive dashboard analyzes and visualizes eBay product data, allowing users to explore pricing trends, brand distribution, and product conditions. The app is built with Streamlit, Pandas, and Plotly, offering a dynamic and user-friendly interface for filtering and analyzing eBay listings.

Application is live at https://ebaydataviz.streamlit.app/
