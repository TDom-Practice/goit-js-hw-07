# JavaScript DOM Model. Events

This project contains solutions focused on DOM model and events.

---

## Project Structure

```
├── js/
│   ├── task-1.js
│   ├── task-2.js
│   └── task-3.js
│   ├── task-4.js
│   ├── task-5.js
│   └── task-6.js
├── index.html
├── .gitignore
├── .prettierrc
├── task-1.html
├── task-2.html
├── task-3.html
├── task-4.html
├── task-5.html
├── task-6.html
└── README.md
```

---

## Tasks

### Task 1 — Categories

File: [js/task-1.js](./js/task-1.js)

Counts and logs the number of categories in `ul#categories` (i.e. `li.item` elements).  
For each category logs the heading text (`h2`) and the number of nested `li` elements.

**Console output example:**

```
Number of categories: 3
Animals: 4 items
Products: 3 items
Technologies: 5 items
```

---

### Task 2 — Image Gallery

File: [js/task-2.js](./js/task-2.js)

Creates an image gallery from the `images` array of objects.  
Each image is rendered as an `<img>` inside an `<li>` element and appended to `ul.gallery` in a single DOM operation.  
Gallery is styled with flexbox.

---

### Task 3 — Greeting

File: [js/task-3.js](./js/task-3.js)

Listens for the `input` event on `#name-input`.  
Updates `#name-output` with the trimmed input value.  
If the input is empty or contains only spaces, displays `"Anonymous"`.

**Example:**

- Type `"Alice"` → greeting reads `Hello, Alice!`
- Clear input → greeting reads `Hello, Anonymous!`

---

### Task 4 — Login Form

File: [js/task-4.js](./js/task-4.js)

Listens for the `submit` event on `.login-form`.  
Prevents page reload.  
Validates that both `email` and `password` fields are filled in - shows an `alert` if not.  
On valid submission, logs an object `{ email, password }` (values trimmed) to the console and resets the form.

---

### Task 5 — Color Changer

File: [js/task-5.js](./js/task-5.js)

On each click of `button.change-color`, sets a random hex background colour on `<body>` and displays the colour value in `span.color`.

---

### Task 6 — Boxes

File: [js/task-6.js](./js/task-6.js)

- **Create** — validates that the input value is between 1 and 100. Renders that many coloured `<div>` boxes inside `#boxes` (clearing any previous ones) and clears the input. The first box is 30×30 px; each subsequent box is 10 px wider and taller. All boxes have a random background colour.
- **Destroy** — removes all boxes from `#boxes`.
