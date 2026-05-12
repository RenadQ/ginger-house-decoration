# ginger-house-decoration
# 🍪 OOP Quiz Baking Game 🎓

An interactive educational web game made by **Renad Alkahtani** ✨
This project turns Object-Oriented Programming revision into a fun baking challenge. Players answer multiple-choice questions, unlock ingredients, bake a dessert, and decorate the final result.

## 🌟 Project Idea

The game is designed to make studying more engaging. Instead of answering quiz questions in a traditional format, the player enters a colorful kitchen, opens ingredient boxes, answers OOP questions, and unlocks baking tools.

The questions are based on **Lecture 07: Object Oriented Programming**, especially the comparison between **Java** and **Python**.

## 🎮 How the Game Works

1. The player enters their name.
2. The game shows a short guide.
3. The player chooses what to bake.
4. Ingredient and tool boxes appear in the kitchen.
5. Each box opens a multiple-choice question.
6. Correct answers unlock items.
7. After unlocking enough items, the player starts baking.
8. The final dessert can be decorated and saved as an image.

## 🧠 Topics Covered

The quiz questions cover important concepts from the lecture, including:

* Java introduction ☕
* Python introduction 🐍
* Java and Python common features
* Cross-platform support
* Standard libraries
* Object-Oriented Programming concepts
* Encapsulation
* Inheritance
* Polymorphism
* Compiler and interpreter differences
* Code execution
* Portability
* Static typing and dynamic typing
* Variables
* Lists and arrays
* Classes and constructors
* Code readability
* Multiple inheritance
* Method overloading and operator overloading
* Source code class and filename relationship
* Language usage

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript
* React CDN
* SVG graphics
* html2canvas
* Google Fonts

## ✨ Main Features

* Cute baking-themed interface 🍰
* Multiple-choice OOP quiz questions
* Correct answer feedback
* Wrong answer feedback
* Ingredient unlocking system
* Timer challenge ⏱️
* Animated kitchen scene
* Graduation-cap character 🎓
* Baking animation
* Decoration screen
* Save final result as an image
* Responsive design for desktop and mobile

## 📁 File Structure

```text
project-folder/
│
├── index.html    # Main game file
└── README.md     # Project documentation
```

If the HTML file has another name, rename it to:

```text
index.html
```

This makes it easier to publish the project using GitHub Pages.

## 🚀 How to Run the Project

### Option 1: Open Directly

1. Download the project files.
2. Open the folder.
3. Double-click `index.html`.
4. The game will open in your browser.

### Option 2: Run with Local Server

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## 🌐 Deploy on GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` and `README.md`.
3. Go to **Settings**.
4. Open **Pages**.
5. Choose:

   * Source: `Deploy from a branch`
   * Branch: `main`
   * Folder: `/root`
6. Save the settings.
7. Wait for GitHub to generate the website link.

## 🎯 Recommended Repository Name

```text
oop-quiz-baking-game
```

## 🔧 How to Edit Questions

Inside the HTML file, find the `ALL_Q` array:

```javascript
var ALL_Q = [
  {
    q: "Question text",
    opts: ["Option A", "Option B", "Option C", "Option D"],
    a: 1
  }
];
```

The value of `a` means the correct answer index:

```text
0 = first option
1 = second option
2 = third option
3 = fourth option
```

## 🧁 How to Add More Items

Find the `RECIPES` object and add a new item to the `shelf` or `counter` list:

```javascript
{id: "newItem", l: "New Item", i: "⭐"}
```

## 🎨 How to Change Colors

Edit the CSS variables inside `:root`:

```css
:root {
  --purple: #7C5CBF;
  --lavender: #E8E0FF;
  --green: #2ECC71;
}
```

## 👩‍💻 Made By

This project was created by **Renad Alkahtani** 💜
Computer Science Student

## 📌 Notes

* This is a frontend-only project.
* No database is required.
* Internet access may be needed for fonts and CDN libraries.
* The project is suitable for academic presentation, course revision, and interactive learning.

## 📜 License

This project is for educational use. You can modify it, improve it, and reuse it for learning purposes.

---

⭐ If you like the project, give it a star on GitHub!
