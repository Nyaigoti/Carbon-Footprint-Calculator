# Carbon Footprint Calculator 🌍

This project is a **Personal Carbon Footprint Calculator** built using Streamlit. It helps users estimate their annual carbon emissions based on their daily activities, including transportation, electricity consumption, diet, and waste generation.

## Features

- **Transportation**: Calculates CO2 emissions based on daily commute distance.
- **Electricity**: Estimates CO2 emissions from monthly electricity consumption.
- **Diet**: Calculates CO2 emissions based on the number of meals consumed daily.
- **Waste**: Estimates CO2 emissions based on weekly waste generation.
- **Total Carbon Footprint**: Provides an overall estimation of the user's carbon footprint.

## Emission Factors

The calculator uses emission factors specific to Kenya, including:

- **Transportation**: 0.14 kg CO2 per km
- **Electricity**: 0.82 kg CO2 per kWh
- **Diet**: 0.97 kg CO2 per meal
- **Waste**: 0.1 kg CO2 per kg of waste

*Note*: Replace these factors with accurate data for more precise calculations.

## Installation

1. **Clone the repository**:
    ```bash
    git clone <REPOSITORY_URL>
    ```
   
2. **Navigate to the project directory**:
    ```bash
    cd carbon-footprint-calculator
    ```

3. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Streamlit app**:
    ```bash
    streamlit run app.py
    ```

## Usage

- Input your daily commute distance, monthly electricity consumption, weekly waste generation, and daily meal count.
- Click the "Calculate CO2 Emissions" button to view your carbon emissions by category and your total carbon footprint.

## Future Enhancements

- Add support for multiple countries with different emission factors.
- Include additional categories such as water usage and air travel.
- Provide tips for reducing carbon footprints.


## Acknowledgements

- Emission factors and data sources.
- Streamlit for the easy-to-use app framework.
