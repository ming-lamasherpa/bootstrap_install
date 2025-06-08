# bootstrap_install
Step 1: Install Bootstrap via NPM
-> Run this command in your project folder:
npm install bootstrap
✅ Step 2: Import Bootstrap CSS into your project
Open the file:
📂 src/index.js
(or src/main.jsx if you're using newer setups like Vite or custom builds).
Add this import line at the very top:
=> import 'bootstrap/dist/css/bootstrap.min.css';

Your index.js should now look something like this:
import React from 'react';
import ReactDOM from 'react-dom/client';
import './index.css';
import App from './App';
import 'bootstrap/dist/css/bootstrap.min.css';

const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(<App />);

 Step 3: Try Using Bootstrap
Edit your App.js to test it out:
function App() {
  return (
    <div className="container mt-5">
      <h1 className="text-primary">Hello Bootstrap in React!</h1>
      <button className="btn btn-success">Click Me</button>
    </div>
  );
}

