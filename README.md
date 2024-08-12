# Hotel Recommender System

This repository contains a hotel recommender system that utilizes content-based filtering to recommend hotels based on user preferences and historical data. The system is built using Python and leverages various libraries for data manipulation, analysis, and user interaction.

## Features

- **Data Integration**: Merges multiple datasets including hotel details, room prices, and amenities.
- **Recommendation System**: Implements a content-based filtering approach to recommend hotels based on user input.
- **User Interface**: Provides a user-friendly interface using Streamlit for easy interaction and hotel recommendations.

## Datasets

- `Hotel_details.csv`: Contains information about hotels including their name, address, city, country, property type, star rating, and amenities.
- `hotel_price_min_max - Formula.csv`: Contains price range information for different hotel codes.
- `hotels_RoomPrice.csv`: Provides detailed room pricing and amenities information.

## Libraries Used

```python
import pandas as pd
import numpy as np
import streamlit as st
from sklearn.preprocessing import LabelEncoder
from sklearn.metrics.pairwise import cosine_similarity

