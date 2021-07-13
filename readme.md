## DataMaps Country API

The country API modifies the [World Happiness Report 2021](https://www.kaggle.com/ajaypalsinghlo/world-happiness-report-2021) dataset to include
- Country Capital cities
- latlng values Address values encodable by Google maps
- potentially over 20+ data points about a country 

The additional data points improve the quality of information from this dataset and makes the csv file directly 'importable' on the DataMaps platform for visualization

**Package dependencies :**
- python-requests api
- googlemaps geocoder api
- load_dotenv ; os;
- pandas
