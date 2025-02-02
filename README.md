# Health Map : Real-Time Hospital Locator for AETNA Insurance Holders

A web application developed to display real-time hospital locations that accept AETNA insurance using Google Places API. It provides interactive location-based information for users to explore hospitals and their related details.

## Features

- **Real-time Hospital Data**: The application fetches real-time hospital data and displays it on the map.
- **Interactive Map**: Users can interact with the map to view hospitals in different locations and retrieve information.
- **Location-based Information**: Detailed information about each hospital is displayed when clicked on the map marker.
- **Deployment with Docker**: Both frontend and backend components are containerized using Docker for easy deployment and scalability.
- **Backend Development with Spring**: The backend of the application is developed using the Spring framework.
- **Frontend Development with Streamlit**: Streamlit is used to develop the frontend of the application, providing a smooth and interactive user experience.
- **Deployment on AWS EKS and ECS**: The application is deployed on Amazon Web Services using Elastic Kubernetes Service (EKS) and Elastic Container Service (ECS) for efficient management and scaling.

## Installation of frontend

1. Clone the GitHub repository:

```bash
git clone https://github.com/AvaniVaidya/Medical-Services-Web-App.git
```

2. Navigate to the medical-services-frontend project directory:

```
cd medical-services-frontend
```

3. Install docker (on MacOS):

```
brew install docker
```

4. Docker build:

```
docker-compose up --build
```

5. Navigate to the medical-services-backend project directory:

```
cd medical-services-backend
```

6. Install docker (on MacOS):

```
brew install docker
```

7. Docker build:

```
docker-compose up --build
```

8. Access the application by visiting :

```
http://localhost:8080
```

## Contributing:

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

- Fork the repository.
- Create a new branch (git checkout -b feature/your-feature).
- Make your changes and commit them (git commit -am 'Add some feature').
- Push to the branch (git push origin feature/your-feature).
- Create a new Pull Request.

## Acknowledgements

This project acknowledges the following technologies and platforms:

- **Google Maps API**: Provides the mapping functionality.
- **Spring**: Powers the backend development.
- **Streamlit**: Used for frontend development.
- **Docker**: Enables containerization for the project.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
