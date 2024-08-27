body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    text-align: center;
    padding: 20px;
    background-color: #007bff;
    color: white;
}

h1 {
    margin: 0;
    font-size: 2.5rem;
}

p {
    margin: 10px 0;
}

main {
    padding: 20px;
}

#tracker {
    margin-bottom: 40px;
}

#habits-container {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
}

.habit-grid {
    display: grid;
    grid-template-columns: repeat(31, 1fr);
    gap: 5px;
    border: 1px solid #ccc;
    padding: 10px;
    background-color: white;
}

.habit-grid .day {
    width: 20px;
    height: 20px;
    background-color: #f0f0f0;
    text-align: center;
    line-height: 20px;
    cursor: pointer;
}

.habit-grid .day.completed {
    background-color: #28a745;
    color: white;
}

#add-habit-btn {
    padding: 10px 20px;
    font-size: 1rem;
    background-color: #28a745;
    color: white;
    border: none;
    cursor: pointer;
}

#add-habit-btn:hover {
    background-color: #218838;
}

#graph {
    margin-top: 40px;
    text-align: center;
}
