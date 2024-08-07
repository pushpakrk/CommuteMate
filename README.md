# CommuteMate

CommuteMate is a carpooling application designed to facilitate ride sharing among users. This project consists of a frontend built with Angular and backends using Django (Python) and Spring Boot (Java).

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Features

- User Registration
- Ride Posting
- Ride Matching
- Verification
- Messaging
- Rating

## Technologies Used

### Frontend

- Angular
- HTML
- CSS

### Backend

- Python (Django)
- Java (Spring Boot)

### Other

- TypeScript
- Node.js



## Setup and Installation

### Prerequisites

- Node.js and npm
- Angular CLI
- Python 3.x and pip
- Java 8 or higher
- Django
- Spring Boot

### Frontend

1. Clone the repository:

```bash
git clone https://github.com/yourusername/CommuteMate.git
cd CommuteMate/frontend
```

2. Install dependencies:

```bash
npm install
```

3. Run the Angular development server:

```bash
ng serve
```

### Backend

#### Python (Django)

1. Navigate to the Django backend directory:

```bash
cd CommuteMate/backend/python
```

2. Create a virtual environment and activate it:

```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run the Django development server:

```bash
python manage.py runserver
```

#### Java (Spring Boot)

1. Navigate to the Spring Boot backend directory:

```bash
cd CommuteMate/backend/java
```

2. Build and run the Spring Boot application:

```bash
./mvnw spring-boot:run
```

## Usage

1. Open a web browser and navigate to `http://localhost:4200`.
2. Use the navigation links to register, publish a ride, and view the profile.

## API Endpoints

### User Registration

- **URL:** `/api/auth/register`
- **Method:** POST
- **Backend:** Django

### Ride Posting

- **URL:** `/api/rides`
- **Method:** POST
- **Backend:** Django

### Ride Matching

- **URL:** `/api/ride-matching`
- **Method:** GET
- **Backend:** Spring Boot

### Verification

- **URL:** `/api/verification`
- **Method:** POST
- **Backend:** Spring Boot

### Messaging

- **URL:** `/api/chat`
- **Method:** POST
- **Backend:** Django

### Rating

- **URL:** `/api/ratings`
- **Method:** POST
- **Backend:** Django

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
