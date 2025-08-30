# 🎵 Band Name Generator

This is a beginner-friendly Python program that generates a fun **band name** based on user input.  
It asks for the city where you were born and your pet’s name, then combines them to suggest a unique band name.

---

## 📌 How It Works
1. The program displays a welcome message.  
2. It asks the user for:
   - The city they were born in
   - Their pet’s name  
3. It combines both inputs and prints out a possible band name.

---

## 🖥️ Code Example

```python
print("Welcome To Band Generator")
city = input("Which City You Have Born?\n ")
petname = input("what is your pet name?\n ")
print("Your Band Name Could Be " + city + " " + petname)
