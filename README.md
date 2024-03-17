# Simple HTTP Server in Go

This is a simple HTTP server implementation in Go, designed to handle basic HTTP requests and responses. It can be used for various purposes like serving static files, building APIs, or handling webhooks.

## Installation

Ensure you have Go installed on your machine. You can download and install it from the [official Go website](https://golang.org/).

Clone this repository:

```bash
git clone https://github.com/yourusername/your-http-server.git
```

## Usage

1. Navigate to the directory where you cloned the repository.
2. Build the executable:

```bash
go build
```

3. Run the server

```bash
go run main.go
```

4. Open localhost:8080 your web browser 

## Endpoints

- **GET /hello**

  Returns a simple "Hello, World!" message.

- **GET /form.html**

  Html form to send to the server.

- **GET /form**

  Returns the submitted value from the form.


## Example

To access the server running locally:

- Open your web browser and visit `http://localhost:8080/hello` to see the "Hello, World!" message.
- Visit `http://localhost:8080/form.html` to fill out the form.
- Visit `http://localhost:8080/form` to see the result from the submitted form.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the [MIT License](LICENSE).