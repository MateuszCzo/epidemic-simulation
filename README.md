# Epidemic Simulation

## Project Description
### Project Goal
The project aims to create an application that simulates and visualizes the progression of epidemics. Users can model the spread of diseases such as COVID-19 or the flu by inputting parameters like initial infection numbers, transmission rates, and mortality rates. It is important to note that this project is purely a programming exercise and I am not an epidemiologist.

### Features
Create and Manage Simulations: Define new epidemic scenarios and manage them.
Track Epidemic Progress: Monitor how the number of infected, healthy, deceased, and recovered individuals changes over time.
Data Visualization: Present simulation results through clear charts and tables.

### Overview
The application helps users understand the dynamics of epidemics and their impact on populations through interactive models and visualizations. This project is intended for educational and exploratory purposes only and is not based on professional epidemiological expertise.

## How to Run the Application
### Prerequisites
* Docker

### Running the Application
1. Clone the repository to your local machine:
git clone https://github.com/MateuszCzo/epidemic-simulation.git
2. Change directory to project folder:
```cd epidemic-simulation```

2. Ensure that the following ports are open on your system:
* 5432: PostgreSQL database
* 8080: Spring server
* 4200: Angular application

3. Build and start the application using Docker Compose:
```docker compose up```

5. Access the application in your web browser at http://localhost:4200.

### Stopping the Application
To stop the application, press Ctrl+C in the terminal where Docker Compose is running, or run the following command in the project directory:
```docker compose down```

## Troubleshooting
If you encounter the following error: ```[epidemic_backend builder  7/10] RUN ./mvnw dependency:go-offline:
0.645 /bin/sh: ./mvnw: not found```

Please visit https://stackoverflow.com/questions/52748640/unable-to-run-mvnw-clean-install-when-building-docker-image-based-on-openjd for further instructions or consider downloading the project as a .zip file. :)
