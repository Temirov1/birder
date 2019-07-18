Birder
======

Brider is a convinient clone of Twitter

## Setup

1. Clone the repository

```bash
git clone https://github.com/Temirov1/birder.git
```

2. Configure the server. Create the `.env` file
   specifying the database and web server configuration parameters.

```bash
# Inside .env file...

# Database Configuration
BIRDER_DB_HOST=
BIRDER_DB_PORT=
BIRDER_DB_NAME=
BIRDER_DB_USER=
BIRDER_DB_PASSWORD=
BIRDER_DB_DIALECT=

# Web Server Configuration
BIRDER_PORT=


# Web App Configurations
BIRDER_ADMIN_LOGIN=
BIRDER_ADMIN_PASSWORD=
```
3. Install all the dependecnies.

```bash
npm install
```

## Credits

Temirov Kurmanbek <kurmanbek12@gmail.com>

4. Start the server