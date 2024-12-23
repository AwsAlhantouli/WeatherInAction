This project demonstrates the processing and visualization of real-time weather data. Data is fetched using an API key and processed through a Kafka messaging system and Apache Spark for large-scale data handling. The results are then showcased using Streamlit, creating an interactive dashboard for users to explore.
Project Overview

In this project, I built a data pipeline that fetches weather data from an external API and processes it using Kafka and Apache Spark. The processed data is then visualized in an interactive Streamlit dashboard that allows users to view weather trends and forecasts.
Key Features:

    Real-Time Data Processing: Data is streamed in real time via Kafka and processed in parallel using Apache Spark for efficient computation.

    Streamlit Dashboard: The data is presented through a user-friendly interface built with Streamlit, allowing users to interact with the visualizations.

    Data Visualizations: The weather data is visualized in various formats, such as line graphs and heat maps, to provide a clear understanding of weather patterns.

Technologies Used:

    Python
    Kafka for data streaming
    Apache Spark for distributed data processing
    Streamlit for building the interactive dashboard
    Matplotlib and Seaborn for data visualization

Project Goals:

    Implement a real-time data pipeline for fetching and processing weather data.
    Build an interactive dashboard for users to explore and analyze the weather data.
    Demonstrate the power of Kafka and Spark for handling large-scale real-time data.
