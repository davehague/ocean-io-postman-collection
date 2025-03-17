# Ocean.io API Postman Collection

This repository contains a ready-to-use Postman collection for the [Ocean.io API](https://ocean.io/), designed to simplify exploration and testing of the API's endpoints. Whether you're just getting started or looking for a reference setup, this collection provides a convenient, structured way to interact with Ocean.io’s endpoints.

## Features

- **Pre-configured Postman Collection** based on Ocean.io's official OpenAPI specification.
- **Environment Setup** with variables to streamline authentication and endpoint usage.
- Token management via `OCEANIO_API_TOKEN` environment variable for secure, reusable requests.
- Adjusted and cleaned requests based on practical testing and findings.

## Getting Started

### Prerequisites

- [Postman](https://www.postman.com/downloads/) installed
- A valid Ocean.io API token

### Installation

1. **Clone this repository**:

   ```bash
   git clone https://github.com/your-username/oceanio-postman-collection.git
   cd oceanio-postman-collection
   ```

2. **Import Collection and Environment** into Postman:

   - Import `collection/Oceanio.postman_collection.json` into Postman.
   - Copy and rename `environment/Oceanio.postman_environment.template.json` to `environment/Oceanio.postman_environment.json` and import into Postman

3. **Set API Token**:
   - In Postman, select the `Oceanio` environment.
   - Set the `OCEANIO_API_TOKEN` environment variable to your actual token.

### Usage

Once set up, you can:

- Easily test endpoints without manually adding headers or tokens.
- Modify or extend requests to suit your use case.
- Save time during API integration or debugging.

## Notes & Customization

- Several endpoints are configured to dynamically use the `{{OCEANIO_API_TOKEN}}` variable.
- Any quirks or limitations discovered during testing are documented within request descriptions.
- You can further customize the environment or collection as needed.

## Folder Structure

```
/
├── collection/
│   └── Oceanio.postman_collection.json
├── environment/
│   └── Oceanio.postman_environment.template.json
├── .gitignore
└── README.md
```

## Contributing

If you discover improvements, fixes, or additional endpoints, feel free to open a pull request or issue!
