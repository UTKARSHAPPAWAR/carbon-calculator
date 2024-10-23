# 🌍 Carbon Emission Calculator

This project is an interactive **Carbon Emission Calculator** built using **Streamlit** for the web interface and **Plotly** for data visualization. The calculator uses emission factors to estimate the environmental impact of various activities such as transportation, electricity, diet, and waste, specific to different countries across the globe.

---

## 🚀 Features

- **Country-Specific Data**: Provides carbon emission factors for numerous countries across continents.
- **Interactive Visualization**: Uses **Plotly** to create engaging, interactive charts for emission comparison.
- **User-Friendly Interface**: Built with **Streamlit** to ensure a seamless, intuitive experience.
- **Multiple Emission Categories**: Calculates emissions across four categories:
  - Transportation
  - Electricity
  - Diet
  - Waste

---

## 🗂️ Code Structure

1. **Imports and Setup**:
   - The app uses `streamlit` for the frontend interface and `plotly.express` for creating visualizations.
   - **Pandas** is used for data manipulation.
   - Emission factors are stored in a dictionary for various countries.

2. **Global Emission Factors**:
   - The script defines a large dictionary `EMISSION_FACTORS` that holds emission values for different countries categorized by continents (e.g., Africa, Asia, Europe).

3. **User Interface**:
   - Streamlit is used to create a dropdown interface where users can select their country and activities.
   - Users can select emission factors for their region and get real-time feedback on their carbon emissions through graphs.

4. **Visualization**:
   - The app utilizes **Plotly** to generate interactive pie charts and bar charts, providing a visual breakdown of the emissions in different categories.

5. **Output**:
   - The application computes the total carbon footprint based on the user’s selections and displays it in an easy-to-read format with charts.
  
---

## 🛠️ Installation Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/carbon-emission-calculator.git
   cd carbon-emission-calculator
   ```
2. **Install Dependencies**:
   ```
   pip install streamlit numpy pandas matplotlib
   ```
3. **Run the Application**:
   ```
   streamlit run app.py
   ```

---
## 🎨 Usage

1. **Select Your Country**:  
   Choose your country from the dropdown menu.

2. **Choose Activity**:  
   Select different emission categories like transportation, electricity, diet, and waste.

3. **View Results**:  
   Check out the interactive pie charts and bar graphs showing your carbon emissions based on the selected activities.

4. **Analyze and Compare**:  
   Adjust selections to see how different activities affect your overall carbon footprint.
