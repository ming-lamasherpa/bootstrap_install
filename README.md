# 🚀 Bootstrap Setup in React

## 1️⃣ Install Bootstrap
```bash
npm install bootstrap

2️⃣ Import Bootstrap CSS
Add this to src/index.js (or main.jsx if using Vite):
import 'bootstrap/dist/css/bootstrap.min.css';

Example index.js:
import React from 'react';
import ReactDOM from 'react-dom/client';
import App from './App';
import 'bootstrap/dist/css/bootstrap.min.css';

const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(<App />);

3️⃣ Use Bootstrap in Components
Edit App.js:
function App() {
  return (
    <div className="container mt-5">
      <h1 className="text-primary">Hello Bootstrap in React!</h1>
      <button className="btn btn-success">Click Me</button>
    </div>
  );
}
export default App;
