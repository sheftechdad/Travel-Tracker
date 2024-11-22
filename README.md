
# 🌍 Travel Tracker

A web application to 📍 track the places you've visited! Enter the name of the country you visited, and the app will save it to a PostgreSQL database, ensuring the first letter of the country name is always capitalized.

## ✨ Features

-   📝 Record and store visited countries.
-   🔠 Input take first letter capital to add the country in map.
-   🎨 Simple and elegant user interface using HTML and CSS.
-   ⚡ Backend powered by Node.js and Express.js.
-   💾 Persistent storage with PostgreSQL.

## 🛠️ Tech Stack

-   **Backend:** Node.js, Express.js
-   **Database:** PostgreSQL
-   **Middleware:** body-parser
-   **Frontend:** HTML, CSS

## 🚀 Prerequisites

-   📦 Node.js and npm installed.
-   🐘 PostgreSQL installed and running.

## 🔧 Installation

1.  Clone this repository:
    
    ```bash
    git clone https://github.com/sheftechdad/travel-tracker.git  
    cd travel-tracker  
    
    ```
    
2.  Install dependencies:
    
    ```bash
    npm install  
    
    ```
    
3.  Set up the PostgreSQL database:
    
    -   Create a database named `travel_tracker`.
    -   Run the following SQL to create the `countries` table:
        
        ```sql
        CREATE TABLE countries (  
            id SERIAL PRIMARY KEY,  
            name VARCHAR(255) NOT NULL  
        );  
        
        ```
        
4.  Configure the database connection:
    
    -   Add the following environment variables:
        
        ```plaintext
        DB_HOST=localhost  
        DB_USER=your_username  
        DB_PASSWORD=your_password  
        DB_NAME=travel_tracker  
        DB_PORT=5432  
        
        ```
        
5.  Start the application:
    
    ```bash
    node index.js  
    
    ```
    
6.  🌐 Open your browser and navigate to `http://localhost:3000`.
    

## ✍️ Usage

1.  Enter the name of the country you visited in the input field.
2.  ✅ The application will save the country to the database, ensuring the first letter is capitalized.
3.  📜 View the list of all visited countries.

## 📂 Project Structure

```
travel-tracker/  
│  
├── app.js            # Main application file  
├── public/           # Static assets (CSS, images)  
├── views/            # HTML templates  
├── routes/           # Express.js routes  
├── package.json      # Project metadata and dependencies  
└── README.md         # Project documentation  

```

## 🌟 Future Enhancements

-   🗑️ Add functionality to add family member and their visited countries.
-   🗺️ Include a map to visualize visited places.

## 🤝 Contributing

Feel free to fork this project, create a branch, and submit a pull request. Contributions are welcome!

## 📜 License

This project is licensed under the MIT License.

----------

🎉 **Happy Traveling and Tracking!** 🌟

----------

