# Coca-Cola-Sales-Dashboard

Creating a Power BI dashboard for Coca-Cola from scratch using a made-up dataset is an excellent way to showcase data analysis and visualization skills. Let's walk through the process of building this dashboard step by step.

## Data Import and Preparation

First, we'll upload our fictional Coca-Cola dataset from Excel using Power Query:

1. Open Power BI Desktop and click "Get Data"
2. Select "Excel" as the data source
3. Navigate to and select our Coca-Cola Excel file
4. In the Navigator, choose the relevant sheets to import
5. Click "Transform Data" to open Power Query Editor

In Power Query, we'll perform necessary data cleaning and transformations:

- Remove any unnecessary columns
- Ensure correct data types for each column
- Create calculated columns if needed (e.g., Profit Margin = (Revenue - Cost) / Revenue)
- Merge or append tables if data is spread across multiple sheets

Once the data is clean and properly structured, click "Close & Apply" to load it into Power BI.

## Dashboard Structure

Next, we'll create the basic structure of our dashboard:

1. Add a title "Coca-Cola Sales Dashboard" using a text box
2. Create sections for each visual using shapes and text boxes
3. Use a consistent color scheme based on Coca-Cola's branding (red, white, and black)

## Key Visuals

Now, let's create the specified visuals:

### 1. AI-powered Q&A Visual

1. From the Visualizations pane, select the Q&A visual
2. Place it prominently on the dashboard
3. Configure the visual to allow users to ask natural language questions about the data

### 2. Key Influencers for Profit Margins

1. Add a Key Influencers visual to the dashboard
2. Set "Profit Margin" as the metric to analyze
3. Add relevant fields like "Brand," "Region," and "Product Type" as explanatory factors

### 3. Map Chart for Regional Sales

1. Insert a Map visual
2. Use "Region" or "Country" for the Location field
3. Set "Sales" as the Size field to represent sales volume
4. Customize colors and tooltips for better readability

### 4. Matrix for Financial Analysis

1. Add a Matrix visual to the dashboard
2. Use "Product" or "Brand" for rows
3. Add "Price per Unit" and "Operating Profit" as values
4. Format the matrix for clarity, including conditional formatting if desired

### 5. Dynamic Timeline

1. Insert a Timeline slicer
2. Connect it to the date field in your dataset
3. Configure it to allow users to select custom date ranges
4. Ensure all visuals are connected to this timeline for dynamic filtering

## Final Touches

To complete the dashboard:

1. Add slicers for key dimensions like Brand or Product Category
2. Implement cross-filtering between visuals
3. Add data labels and tooltips to enhance information display
4. Optimize the layout for different screen sizes
5. Test the dashboard thoroughly to ensure all interactions work as expected

By following these steps, you'll create a comprehensive and interactive Coca-Cola sales dashboard in Power BI, showcasing various aspects of the business from sales and profit margins to regional performance and financial metrics.
