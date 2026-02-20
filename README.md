# ⭐ Star Rating React Component

A lightweight, customizable, and reusable star rating component for React applications.

Perfect for product reviews, feedback systems, and user ratings.

---

## ✨ Features

* ⭐ Interactive star rating UI
* 🎨 Custom colors and sizes
* 🖱️ Hover preview before selecting
* 💬 Optional rating messages
* ⚡ Lightweight and easy to use
* ♻️ Fully reusable component

---

## 📦 Installation

```bash
npm install @yannickbaze/star-rating
```

or

```bash
yarn add npm install @yannickbaze/star-rating
```

---

## 🚀 Usage

```jsx
import StarRating from "@yannickbaze/star-rating";

function App() {
  return (
    <StarRating
      maxRating={5}
      messages={["Bad", "Okay", "Good", "Very Good", "Excellent"]}
      onSetRating={(rating) => console.log(rating)}
    />
  );
}

export default App;
```

---

## ⚙️ Props Default Values 

`maxRating: 5 (number)`
`defaultRating: 0 (number)`
`color: #fcc419 (string)`
`size: 30 (number)`
`messages: 5 ([])`
`className: - (string)`
`onSetRating: 5 (function, callback when rating is selected)`

| Prop            | Type     | Default   | Description                      |
| --------------- | -------- | --------- | -------------------------------- |
| `maxRating`     | number   | `5`       | Total number of stars            |
| `defaultRating` | number   | `0`       | Initial rating value             |
| `color`         | string   | `#fcc419` | Star color                       |
| `size`          | number   | `30`      | Star size in pixels              |
| `messages`      | string[] | `[]`      | Text shown for each rating       |
| `className`     | string   | —         | Custom CSS class                 |
| `onSetRating`   | function | —         | Callback when rating is selected |

---

## 🎨 Customization Example

```jsx
<StarRating
  maxRating={10}
  size={40}
  color="tomato"
  messages={[
    "Terrible",
    "Bad",
    "Okay",
    "Good",
    "Great",
    "Excellent",
    "Amazing",
    "Superb",
    "Outstanding",
    "Perfect",
  ]}
/>
```

---

## 🧠 How It Works

* Hover over stars to preview rating
* Click to select a rating
* Optional messages update dynamically
* Callback returns selected value

---

## 🛠️ Example With Callback

```jsx
<StarRating
  onSetRating={(rating) => alert(`You rated: ${rating}`)}
/>
```

---

## 📄 License

MIT © 2026

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

If you like this project, give it a ⭐ on GitHub.
