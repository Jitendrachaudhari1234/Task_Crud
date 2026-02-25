## ❓ **FAQ - Common Questions** (Click to Expand Answers)

<details>
<summary>🚀 Q1: Yeh project kaise chalaye?</summary>

1. `index.html` file browser mein open karo.
2. Task type → **Save Task**.
3. Edit/Delete buttons use karo.

**Demo**: [Live Link](https://github.com/Jitendrachaudhari1234/Task_Crud)

</details>

<details>
<summary>⚡ Q2: Data refresh pe kyun gayab ho jaata hai?</summary>

Abhi **LocalStorage nahi** hai. Future mein add karenge:
```js
localStorage.setItem('tasks', JSON.stringify(tasks));
tasks = JSON.parse(localStorage.getItem('tasks') || '[]');