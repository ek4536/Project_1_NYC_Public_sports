# NYC Public Sports Facilities Navigator 🗽

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A Python-based command-line tool for finding the nearest public sports facilities in New York City.



---

## 📖 About The Project

This tool utilizes public data to analyze and locate sports facilities across New York City. When a user enters a location (address or zipcode) and a desired sport, the navigator finds the five nearest public facilities.

This navigator was created based on my personal experiences after moving to NYC. It is designed to be useful for people searching for new hobbies, as well as for those who have recently relocated to New York, helping them easily find the sports facilities they're looking for.

*(This navigator was developed with the help of generative AI.)*

---

## ✨ Features

* **Distance-Based Search**: Finds the closest facilities based on geographic distance, not just zip code proximity.
* **Flexible Location Input**: Accepts both street addresses and 5-digit zipcodes.
* **Wide Range of Sports**: Supports searches for over 20 different sports, including basketball, soccer, tennis, and more.
* **Command-Line Interface**: Easy-to-use interactive prompts directly in your terminal.
* **Efficient Caching**: Pre-processes and caches data locally for significantly faster startups on subsequent runs.

---

## 🛠️ Built With

This project was built using the following technologies:

* **Language**: Python 3
* **Libraries**:
    * Pandas
    * Geopy
    * PyArrow

---

## ⚙️ Getting Started

Follow these steps to get a local copy up and running.

### Prerequisites

Make sure you have Python 3 installed on your system.

### Installation

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/ek4536/Project_1_NYC_Public_sports.git](https://github.com/ek4536/Project_1_NYC_Public_sports.git)
    ```

2.  **Navigate to the project directory**
    ```bash
    cd Project_1_NYC_Public_sports
    ```

3.  **Install required packages**
    It's recommended to use a virtual environment. The necessary packages are listed in `requirements.txt`.
    ```bash
    pip install -r requirements.txt
    ```
    *(If a `requirements.txt` file is not available, install manually: `pip install pandas geopy pyarrow`)*


### Usage

1.  **Run the application**
    ```bash
    python main.py
    ```

2.  **Follow the prompts**
    The program will ask you to enter a location (address or zipcode) and a sport type. The results will be displayed directly in the terminal.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
