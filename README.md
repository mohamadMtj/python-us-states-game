# python-us-states-game
A Python guessing game that uses Turtle graphics and Pandas to identify and display the 50 US states on a map.
# 🇺🇸 US States Game

An interactive **US States guessing game** built with Python using **Turtle graphics, Pandas, and CSV data**.

The goal is to correctly guess all 50 US states and place their names on the map.

This project was created as part of my Python learning journey to practice working with external data, CSV files, Pandas DataFrames, and Turtle graphics.

---

## 🎮 Features

- 🇺🇸 Interactive map of the United States
- ⌨️ User input for guessing states
- 📍 Displays correctly guessed states on the map
- 📊 Tracks the number of correct guesses
- 🐼 Uses Pandas to work with CSV data
- 📁 Uses CSV files for state and coordinate data
- 📝 Generates a list of missing states when the player exits
- 🐢 Uses Turtle for graphical interaction

---

## 🛠 Technologies Used

- Python 3
- Pandas
- Turtle
- CSV

---

## 📂 Project Structure

```text
python-us-states-game/
│
├── main.py
├── 50_states.csv
├── blank_states_img.gif
├── state_to_learn.csv
└── README.md
```

---

## 📊 Dataset

The project uses a CSV file containing the names and coordinates of the US states.

The data is loaded using Pandas:

```python
data = pandas.read_csv("50_states.csv")
```

The state names are then converted into a list:

```python
all_state = data.state.to_list()
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/python-us-states-game.git
```

### 2. Navigate to the project

```bash
cd python-us-states-game
```

### 3. Install Pandas

```bash
pip install pandas
```

### 4. Run the game

```bash
python main.py
```

---

## 🎯 How to Play

1. Run the program.
2. A map of the United States will appear.
3. Enter the name of a US state.
4. If the answer is correct, the state name will appear on the map.
5. Continue guessing until all 50 states are found.
6. Type `Exit` to stop the game.
7. The states you haven't guessed will be saved to a CSV file for later study.

---

## 📈 Learning Objectives

This project helped me practice:

- Working with CSV files
- Pandas DataFrames
- Reading data with Pandas
- Filtering DataFrames
- Converting DataFrame columns to lists
- Working with `.item()`
- Creating new CSV files
- User Input
- Lists
- Loops
- Conditional Statements
- Turtle Graphics
- Working with coordinates
- Combining multiple Python libraries

---

## 🐼 Pandas Usage

One of the main goals of this project was to practice working with **Pandas**.

For example, the program loads the state dataset:

```python
data = pandas.read_csv("50_states.csv")
```

Then it creates a list containing all state names:

```python
all_state = data.state.to_list()
```

When a correct state is entered, the corresponding row is selected from the DataFrame and its coordinates are used to place the state name on the map.

---

## 📁 Missing States

If the player types:

```text
Exit
```

the program finds the states that haven't been guessed yet and saves them to a CSV file.

This can be useful as a simple **study list** for learning the US states.

---

## 💡 Future Improvements

- 🔢 Add a countdown timer
- 🏆 Add a high-score system
- 🎨 Improve the map interface
- 🔊 Add sound effects
- 📊 Show statistics at the end
- 🔄 Add a restart option
- 📚 Create a separate study mode
- 🌎 Add similar games for other countries
- 🖥️ Improve the graphical interface

---

## 👨‍💻 Author

**Mohamad Mtj**

Computer Engineering Student  
Front-End Developer | Python Learner | Linux & Networking Enthusiast

---

## ⭐ Support

If you enjoyed this project, consider giving it a ⭐ on GitHub.
