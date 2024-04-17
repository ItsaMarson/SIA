# Travel Booking System - SIA

## Getting Started

### Setting Up Python Environment

1. Create a Python virtual environment:
    ```bash
    python -m venv .venv
    ```
    
2. Activate the environment:
    - On Windows:
        ```bash
        ./.venv/Scripts/Activate
        ```
    - On macOS/Linux:
        ```bash
        source .venv/bin/activate
        ```

### Installing Project Requirements

Install the required dependencies:
```bash
pip install -r requirements.txt
```

### Running the project

1. Navigate to the FlightReservationSystem folder:
    ```bash
    cd FlightReservationSystem
    ```

2. Start the development server:
    ```bash
    python manage.py runserver
    ```

    If there are unapplied migrations to the project, run:
       ```bash
       python manage.py migrate
       ```
