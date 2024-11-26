Certainly! Below is the `README` file in plain text format using markup, which can be saved as a `.txt` file.

```
# Climat Maroc - Analytical Dashboard for Temperature and Humidity Analysis

## Overview

This Streamlit application visualizes geospatial data regarding temperature, humidity, and precipitation in Morocco. It enables users to interactively explore data, filter it, and visualize it on a map, based on specific attributes and spatial queries. The application also allows for the visualization of different climatic conditions across the country over 12 months.

## Features

- **Geospatial Dataset**: Data of 1009 points across Morocco over 12 months, with attributes for temperature, humidity, and precipitation.
- **Interactive Filtering**: Users can filter data by attributes and spatial queries.
- **Map Visualization**: Temperature, humidity, and precipitation are visualized on an interactive map using Folium and GeoParquet.
- **Time-Series Graphs**: Display monthly temperature, humidity, and precipitation data.
- **Export Functionality**: Export filtered results as GeoJSON files.

## Installation Requirements

To run this application, you need to install the following libraries:

```bash
pip install streamlit
pip install folium
pip install geopandas
pip install streamlit-folium
pip install rasterio
pip install streamlit_lottie
pip install json
pip install requests
pip install GDAL==$(gdal-config --version)
pip install branca.colormap
pip install numpy
pip install selenium
pip install --upgrade rasterio
pip install leafmap
pip install streamlit pillow rasterio
```

## Running the Application

1. Clone or download the repository containing the application.
2. Install the required dependencies using the command above.
3. Run the application using Streamlit:

```bash
streamlit run your_app_name.py
```

4. Access the dashboard on the local server. By default, it will be available at `http://localhost:8501`.

## Usage

### Tabs

- **Accueil**: Introduction to the dataset and the geospatial data analysis tools.
- **Cartes Vecteur**: Visualize temperature, humidity, and precipitation data on a vector map.
- **Cartes Raster**: Explore raster-based maps for further analysis.
- **Comparaison**: Compare data across different months or different locations.

### Map Filters

- **Choose Data Column**: Select the attribute (Temperature, Humidity, Precipitation) you want to visualize.
- **Choose Map Option**: Choose between proportional symbols or graph-based symbols.
- **Coordinate Search**: Search for specific coordinates on the map and zoom to them.
- **Attribute Filter**: Filter data based on specific attribute values (e.g., temperature range).
- **Spatial Query**: Apply spatial filters using GeoPandas query syntax.

### Export Functionality

You can filter the data interactively, and once done, you can export the results in GeoJSON format using the download button.

## App Customization

The dashboard is built using the following libraries:

- **Streamlit** for the user interface and interactivity.
- **Folium** for map visualization.
- **GeoPandas** for geospatial data handling.
- **Pandas** for data manipulation.
- **Lottie** for animations.
- **Matplotlib** for plotting graphs.
- **LeafMap** for additional map-related functionalities.

You can further customize this app by modifying the code and adding new features as per your requirements.

## Contributing

Feel free to fork the repository, submit issues, and create pull requests. We welcome any improvements or contributions to enhance the app's functionality.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

You can save this as a `.txt` file, and it will be formatted in a readable markdown-like structure for documentation.
