## About the project

# React.js Vehicle Simulation Application

This project is a React.js application that allows users to create, display, update, and delete Scenarios and Vehicles. Each Scenario can have multiple Vehicles, and users can start a simulation to move the Vehicles based on their parameters. The application uses json-server to store data.

## Project Setup

Follow these steps to set up and run the application locally:

### Prerequisites

1. Node.js and npm should be installed on our machine.

### Installation

1. Clone this repository to our local machine.
2. Navigate to the project directory in the terminal.
3. Install the required dependencies by running the following command:

```bash
npm install

1.Running the Application
Start the json-server to serve the data by running the following command:
npm run server
2.In a separate terminal window, start the React application:
npm start

## Application Structure
The application consists of the following components:

Home: Displays the list of Scenarios on the sidebar. Users can select a Scenario to view its details and start the simulation.
ScenarioForm: Allows users to create a new Scenario by providing a Scenario name and time.
ScenarioDetails: Displays the details of a selected Scenario, including its name and time. Also, it lists the Vehicles associated with the Scenario.
VehicleForm: Enables users to add a new Vehicle to a selected Scenario by providing Vehicle details like name, initial position (X and Y), speed, and direction.
Vehicle: Represents a single Vehicle with its details like name, position, speed, and direction.

**Simulation and Vehicle Movement
Once a Scenario is selected, the user can click the "Start Simulation" button to initiate the Vehicle movement.
The Vehicles move based on their speed and direction within the Scenario's time limit.
If a Vehicle goes outside the graph container's boundaries, it will be hidden.
The simulation will stop automatically once the Scenario time is over.

## Validation
When adding a new Vehicle, the application performs proper validation to ensure that the provided positions (X and Y) are not greater than the graph container's size.
Deployment
The application can be deployed to any platform like Vercel, Netlify, etc., by following these steps:

Build the React application by running the following command:
npm run build

## Conclusion:
This React.js Vehicle Simulation Application provides a user-friendly interface to create, manage, and simulate Scenarios with multiple Vehicles. It offers a simple yet interactive way to visualize the movement of Vehicles within a designated area. The json-server integration allows data persistence, making it easy to maintain the application's state across sessions.

## Live project link

https://scenario-vehicle-debz.netlify.app/

## Preview

![image](https://user-images.githubusercontent.com/67649413/225752761-d4548a20-cf53-46a1-9225-d18519f50c5f.png)
![image](https://user-images.githubusercontent.com/67649413/225752844-302ca0dc-8c7a-4117-b91e-df04729d2940.png)
![image](https://user-images.githubusercontent.com/67649413/225753003-a0393823-927a-491f-8353-94d2363507fb.png)
![image](https://user-images.githubusercontent.com/67649413/225753174-599358a0-4619-4f7b-b60d-dade2a7f7494.png)
![image](https://user-images.githubusercontent.com/67649413/225753206-790208c8-9d07-4ab8-b6aa-794bda3380bc.png)
![image](https://user-images.githubusercontent.com/67649413/225753249-227e532e-3229-48d4-92c6-de5eb9014949.png)

## `Tools Used`

### FRONTEND
- React
- CSS
- Framer motion
### BACKEND
- npm install
- json server
