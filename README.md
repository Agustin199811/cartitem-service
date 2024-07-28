# Cart Item Service for E-commerce Application

This project is a Cart Item Service for an e-commerce clothing application. The Cart Item Service is designed to manage shopping cart items, enabling functionalities such as adding items to the cart, updating quantities, and removing items. By centralizing cart management, it ensures a smooth and consistent shopping experience across the e-commerce platform.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Running the Service](#running-the-service)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Cart Item Service is a RESTful API built using Spring Boot. It provides endpoints for adding, updating, retrieving, and deleting items in the shopping cart. This service plays a crucial role in the e-commerce system by managing the state of users' shopping carts.

## Features

- **Add Items:** Allows users to add products to their shopping carts.
- **Update Quantities:** Enables users to update the quantity of items in their carts.
- **Retrieve Cart Items:** Supports fetching all items currently in a user's cart.
- **Remove Items:** Facilitates the removal of items from the cart.

## Prerequisites

- Java 17 or higher
- Maven 3.6.3 or higher
- Spring Boot 3 or higher

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/Agustin199811/cartitem-service.git
    cd cartitem-service
    ```

2. Build the project using Maven:

    ```sh
    mvn clean install
    ```

## Configuration

The configuration for the Cart Item Service is located in `src/main/resources/application.properties`. Below is an example configuration:

```properties
spring.datasource.url=jdbc:postgresql://clot.cp88o8squjfi.us-east-1.rds.amazonaws.com:3306/clot
spring.datasource.username=root
spring.datasource.password=root1234

```

## Running the Service

To run the service registry, use the following command:

 ```sh
    mvn spring-boot:run
```

## Contributing

Contributions are welcome! If you would like to contribute to this project, please send us an email at
`toapantaagustin9c@gmail.com` with details about your proposed changes or improvements. We look forward to hearing from you!

## License

This project is licensed under the MIT License - see the LICENSE file for details.
