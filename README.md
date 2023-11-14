# capstone_1
YouTube Data Harvesting and Warehousing using SQL, MongoDB and Streamlit
The YouTube Data Harvesting and Warehousing project is designed to enable users to access and analyze data from multiple YouTube channels. Using SQL, MongoDB, and Streamlit, the project develops a user-friendly application for retrieving, saving, and querying YouTube channel and video data.

The project utilizes several key components:

Streamlit: Employed to create a user-friendly UI, Streamlit allows users to interact with the application, performing data retrieval and analysis operations seamlessly.

Python: Python, a powerful programming language known for its simplicity, is the main language used in this project. It's used to create the entire application, from getting data, working with it, analyzing it, to presenting it visually. Python's popularity stems from its ease of learning and understanding, making it ideal for handling various tasks within this project.

Google API Client: The project uses a tool called the Google API Client, which allows it to connect to YouTube's Data API v3. This connection helps in getting important information like channel details, specific video data, and comments from YouTube. Essentially, it allows developers to access and work with a wide range of data available on YouTube.

MongoDB: MongoDB is a type of database that's designed to handle a lot of data and can adapt well to changes in how that data is structured. It's popular among developers because it's great for creating applications that need to grow and change over time. MongoDB stores data in a way that's similar to how information is organized in a JSON file, making it simple for developers to store both structured and unstructured data easily.

PostgreSQL: PostgreSQL is a powerful and reliable tool used to manage and store structured data efficiently. It's like a well-organized storage space for different types of information, offering a wide range of features and abilities to handle data in a sophisticated manner. It's known for its reliability and flexibility in managing data using a language called SQL, allowing users to perform complex operations on their data.

Required Libraries:

1. googleapiclient.discovery
2. streamlit
3. psycopg2
4. pymongo
5. pandas

FEATURES: The following functions are available in the YouTube Data Harvesting and Warehousing application: Retrieval of channel and video data from YouTube using the YouTube API.

Storage of data in a MongoDB database as a data lake.

Migration of data from the data lake to a SQL database for efficient querying and analysis.

Search and retrieval of data from the SQL database using different search options.
