# httpRequest - Simple

This repository features a server-side Google Tag Manager (sGTM) template that streamlines the creation of HTTP requests. Unlike traditional sGTM HTTP request template where you manually write the JSON for the request body—leading to potential syntax errors and formatting issues—this template simplifies the process, eliminating the need to write JSON manually and reducing the risk of mistakes.

You can easily define key-value pairs for request headers and body, and the template compiles all the necessary code in the backend.

![image](https://github.com/user-attachments/assets/e26d4019-ec81-4bd8-a41b-d100bb361b27)



## Features

- Simplifies the creation of HTTP requests in GTM
- Allows easy definition of key-value pairs for headers and body
- Automatically compiles the necessary code in the backend

## Installation

To use this GTM template in your project, follow these steps:

1. Download the template from this repository.
2. In your GTM workspace, go to the Templates section.
3. Click on the "New" button to create a new template.
4. Import the downloaded template file.
5. Save and publish the template.

## Usage

Once the template is installed, you can use it to create HTTP requests as follows:

1. Go to the Tags section in your GTM workspace.
2. Click on the "New" button to create a new tag.
3. Select the `httpRequest` template.
4. Define the key-value pairs for the request headers and body.
5. Save and publish the tag.

## Example

Here is an example of how to use the `httpRequest` template:

1. Create a new tag using the `httpRequest` template.
2. Define the following key-value pairs in the request headers:
   - `Authorization: Bearer <your-token>`
   - `Content-Type: application/json`

3. Define the following key-value pairs in the request body:
   - `name: John Doe`
   - `email: john.doe@example.com`

4. Save and publish the tag.

This will create an HTTP request with the defined headers and body, and the template will compile the necessary code in the backend to send the request.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

