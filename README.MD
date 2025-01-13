# TourAssist: Simplifying Travel Planning

**TourAssist** is an innovative web application designed to empower tour agents to enhance their offerings while providing customers with tools to compare, customize, and book travel packages effortlessly.

---

## About the Project

TourAssist creates a unified marketplace where travel companies, regardless of size, can showcase holiday and travel packages. Customers can discover, personalize, and book these packages through a streamlined and user-friendly interface.

### Highlights

- **Equitable Marketplace**: TourAssist ensures equal visibility for travel companies, enabling both small and large operators to connect with customers on a level playing field.
- **Customizable Packages**: Customers can tailor packages to match their preferences, such as excluding transportation or adding specific activities, with real-time price adjustments.

---

## Getting Started

### Prerequisites

Make sure you have the following software installed:

- [Docker Desktop](https://www.docker.com/products/docker-desktop)

### Configuration

The application relies on several environment variables that can be adjusted as needed. These include:

- `ENV`: Specifies the environment profile for the frontend (default: `dev`)
- `FRONTEND_URL`: URL for the frontend
- `DATASOURCE_URL`: JDBC URL for the MySQL database
- `DATASOURCE_USERNAME`: Database username
- `DATASOURCE_PASSWORD`: Database password

For more details, see the [docker-compose.yaml](./docker-compose.yaml) file.

---

## Running the Application

### Start All Services with the Latest Build

To build and launch the application:
```bash
docker-compose -f docker-compose.yaml up -d --build
