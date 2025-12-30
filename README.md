# Docker Compose for WordPress

A robust Docker Compose configuration for launching a WordPress site with a MySQL database.

## Features

-   **WordPress**: Latest official image.
-   **MySQL**: 5.7 or 8.0 support.
-   **Persistence**: Volumes for `wp-content` and database.
-   **Network**: Private network for DB communication.

## Installation

1.  **Clone the repository**.
2.  **Start Services**:
    ```bash
    docker-compose up -d
    ```
3.  Visit `http://localhost:8000` to finish installation.

## Services

-   **wordpress**: The application server (Port 8000).
-   **db**: The database server (Internal).

## Contact

Developed for Anunzio International by Anzul Aqeel.
Contact +971545822608 or +971585515742.

## License

MIT


---
### 🔗 Part of the "Ultimate Utility Toolkit"
This tool is part of the **[Anunzio International Utility Toolkit](https://github.com/anzulaqeel/ultimate-utility-toolkit)**.
Check out the full collection of **180+ developer tools, scripts, and templates** in the master repository.

Developed for Anunzio International by Anzul Aqeel.
