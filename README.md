# Simple Web App

This is a simple web application project.

## Features
- Lightweight and easy to deploy
- Containerized with Docker
- Ready for cloud or local deployment

## Getting Started

### Prerequisites
- Docker installed on your machine

### Build and Run

1. Clone the repository:
   ```sh
   git clone <repository-url>
   cd simple-web-app
   ```
2. Build the Docker image:
   ```sh
   docker build -t simple-web-app .
   ```
3. Run the container:
   ```sh
   docker run -p 8080:8080 simple-web-app
   ```

## Project Structure
- `Dockerfile` - Docker configuration for building the app image
- `README.md` - Project documentation
- `src/` - Application source code (if present)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License.