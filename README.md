# Fertilizers and Pesticides Advisory System

## Overview
The **Fertilizers and Pesticides Advisory System** is a web-based application designed to assist farmers in optimizing their agricultural practices. The system provides personalized recommendations for fertilizers and pesticides and allows farmers to upload crop images for expert analysis to identify diseases and suggest solutions.

---

## Features

1. **Fertilizer Recommendation**
   - Input crop name, soil type, land area, and pH level.
   - Receive personalized fertilizer suggestions.

2. **Pesticide Recommendation**
   - Input detected diseases or crop conditions.
   - Get recommendations for effective pesticides.

3. **Crop Image Analysis**
   - Farmers can upload crop images.
   - Experts analyze the images to detect diseases and provide solutions.

4. **Expert Consultation**
   - Allows expert users to log in and provide insights.
   - Experts can analyze and respond to uploaded images and data.

---

## Tech Stack

### Frontend:
- **HTML**
- **CSS**
- **JSP** (Java Server Pages)

### Backend:
- **Java** (Servlets for backend logic)
- **MySQL** (Database for storing user inputs, recommendations, and expert analysis)

### Tools:
- **Apache Tomcat** (Server)
- **IntelliJ IDEA** or **Eclipse IDE** (Development Environment)

---

## Installation and Setup

1. **Set Up Database**
   - Create a MySQL database.
   - Import the `database.sql` file from the repository.

2. **Configure Database Connection**
   - Open the project in your IDE.
   - Update the database credentials in the `db-config.properties` file.

3. **Deploy on Apache Tomcat**
   - Build the project.
   - Deploy the WAR file to the `webapps` folder of Tomcat.

4. **Run the Application**
   - Start the Tomcat server.
   - Access the application at `http://localhost:8080/Fertilizers_and_Pesticides_Advisory_System`.

---


## Modules

### Fertilizer Recommendation Module
- Collects input from users such as crop name, soil type, and pH.
- Provides a list of recommended fertilizers.

### Pesticide Recommendation Module
- Suggests pesticides based on user inputs or detected diseases.

### Crop Image Analysis Module
- Allows users to upload crop images.
- Expert users analyze these images to identify crop diseases and suggest solutions.

### Expert Consultation Module
- Enables experts to log in and interact with user-submitted data.
- Experts provide detailed recommendations based on crop conditions.

---

## Future Enhancements

- Integrate AI/ML models for automatic disease prediction.
- Add support for multiple languages.
- Enable real-time notifications and weather updates.

---

## Contributing

1. Fork the repository.
2. Create a new branch for your feature.
3. Commit your changes and open a pull request.

---


## Contact
For any queries or contributions, contact:
- **Name:** Amol Latpate
- **Email:** [amollatpate5979@gmail.com](mailto:amollatpate5979@gmail.com.com)
- **GitHub:** [amollatpate5979](https://github.com/amollatpate5979)
