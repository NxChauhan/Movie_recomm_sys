There are some files which I am not able to upload because of their large size

You can refer to below dataset link for csv files of movies dataset (https://drive.google.com/drive/folders/1dHt8ysKcc9XyhW9eZuavI7ZpKGZvZi0I?usp=sharing)

However there are some pkl files as well which I can not publish so I recommend you to check my code how I created pkl files and run it on your system.

-> **Recommender System.ipynb file** - This file contains the preprocessing of data and implementation of ML cosine algorithm. This file is the initial file in which all the requirements like preprocessing data, crating model for recommendation are done.

-> **About the setup.py File**
This project uses a setup.py file for packaging and distributing the movie recommendation system. Below is a brief explanation of the key components in the setup.py:

    **Package Name**: The source repository is named src.
    **Version**: The current version of the package is 0.0.1.
    **Author**: The package was developed by Nitin Chauhan.
    **Author Email**: For any queries or contributions, you can contact the author at nitinrajput06506@gmail.com.
    **Description:** This package is an example project for building a movie recommendation system using machine learning.
    **Long Description:** The detailed description of the project is extracted from the README.md file using long_description. This helps provide a comprehensive overview on platforms like PyPI.
    **Python Version**: This project requires Python 3.7 or higher.
    **Dependencies**: The package has a list of required dependencies, such as streamlit, which will be automatically installed during setup.
  This file makes it easy to distribute the project and manage its dependencies, ensuring a smooth setup process for users and contributors.

  
-> **About the setup.py File**
  The requirements.txt file contains the necessary dependencies for running the movie recommendation system. Below is an overview of its contents:

    **streamlit:** This is the primary package required for building the web interface of the movie recommendation system. Streamlit allows you to create interactive and dynamic web apps for your machine learning models with minimal effort.
    
    **-e .:** This specifies the local packages to be installed in editable mode. The -e . points to the current directory, indicating that this project is treated as a package during development. It allows the package to be editable so that any changes made to the source code are instantly reflected without needing to reinstall.
    
  This file ensures that all the required dependencies for the project are installed, enabling users to easily set up their environment.


  
