# react-debug-checklist
A checklist for navigating and understanding React codebases.

# 🧭 General React Code Navigation Plan

A tactical checklist to help you comb through any React codebase with clarity and speed. Whether you're debugging, learning, or reviewing someone else's work, this guide helps you stay focused and methodical.

---

## ✅ Checklist

### 1. Identify Components
- [ ] Look for functions that return JSX — those are components.
- [ ] Note the main/root component (usually `App`) and any child components.

### 2. Check State and Props
- [ ] Look for `useState`, `useEffect`, and props passed into components.
- [ ] Ask: *What data does this component track or receive?*

### 3. Read the JSX Return
- [ ] Scan the `return()` block to see what’s rendered.
- [ ] Look for dynamic expressions (`{}`), conditionals, and loops.

### 4. Find Event Handlers
- [ ] Look for functions tied to events like `onClick`, `onChange`, etc.
- [ ] Ask: *What happens when the user interacts?*

### 5. Trace Data Flow
- [ ] Follow how props move from parent to child.
- [ ] Follow how state changes trigger re-renders.

### 6. Check Execution Readiness
- [ ] Make sure each function has the data it needs.
- [ ] Look for missing props, undefined state, or broken logic.

---

## 🧠 Why This Exists

This template was created to help developers—especially those learning React—build a mental map of any codebase they encounter. It reflects a tactical, stepwise approach to understanding component logic, state flow, and UI behavior.

## 📣 Contributions Welcome

Feel free to fork, adapt, or suggest improvements. This is a living doc—let’s make React easier to navigate for everyone.

## 📄 License

This project is licensed under the [MIT License](LICENSE).
