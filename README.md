📌 Live Character Counter for Textarea
📝 Description

This project is a simple web page that contains a textarea where the user can type text. As the user types, a character counter updates instantly and shows the current number of characters entered. This provides clear and immediate feedback to improve the user experience.

🎯 Objective

To implement real-time event handling using JavaScript.

To dynamically update HTML content based on user input.

To practice basic DOM manipulation.

📚 Task Description

Create a web page that includes:

A textarea for user input.

A live character counter that updates whenever the user types or deletes text.

The character counter should display the exact number of characters currently present in the textarea.

✅ Features

Live update of character count

Instant feedback on every keystroke

Clean and simple UI

Beginner-friendly and easy to understand

🛠️ Technologies Used

HTML

CSS

JavaScript

🔧 How It Works

The textarea listens to the input event.

Whenever the user types, .value.length is used to calculate character count.

The counter text updates in real time using JavaScript DOM methods.

👨‍💻 JavaScript Code
const textarea = document.getElementById('text');
const counter = document.getElementById('counter');

textarea.addEventListener('input', () => {
  counter.textContent = textarea.value.length;
});

📷 Expected Output

Displays "Characters: 0" when empty

Shows updated count as the user types

🚀 How to Use

Open the index.html file in your browser.

Start typing in the textarea.

Observe the live character count below.

🏁 Conclusion

This mini project is useful for understanding:

Real-time interactivity

DOM updates

Event listeners in JavaScript
Live Link :- https://dommanipulationusingjava.bytexl.live/
