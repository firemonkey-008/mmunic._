body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: space-between;
}

nav li {
    margin-right: 20px;
}

.background-image {
    background-size: cover;
    background-position: center;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    color: #fff;
}

section {
    padding: 20px;
}

#comentarios-list {
    list-style: none;
    padding: 0;
    margin: 0;
}

#comentarios-list li {
    margin-bottom: 10px;
    padding: 10px;
    border-bottom: 1px solid #ccc;
}

#comentarios-list li:last-child {
    border-bottom: none;
}

form {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 20px;
}

label {
    margin-bottom: 10px;
}

input, textarea {
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ccc;
}

input[type="submit"] {
    background-color: #333;
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

input[type="submit"]:hover {
    background-color: #444;
}
