# ium
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f9f9f9;
}

.screen {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
}

.hidden {
  display: none;
}

header {
  width: 100%;
  background-color: #4CAF50;
  color: white;
  text-align: center;
  padding: 10px 0;
}

nav button {
  margin: 5px;
  padding: 10px 20px;
  background-color: #fff;
  border: none;
  cursor: pointer;
}

form {
  display: flex;
  flex-direction: column;
  gap: 10px;
  width: 300px;
}

form input, form button {
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

button {
  background-color: #4CAF50;
  color: white;
  border: none;
  padding: 10px;
  cursor: pointer;
}

button:hover {
  background-color: #45a049;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  background-color: #e7f3e7;
  padding: 10px;
  margin: 5px 0;
  border-radius: 5px;
}
