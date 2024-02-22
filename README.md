<div align="center">

<img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Logo" width="80" height="80">

# Empress JS SDK: The Ultimate Bridge to Framework Backend

Welcome to the Empress JS SDK, a robust TypeScript/JavaScript library that facilitates seamless interaction with a Framework backend. 

[Explore the Docs](https://grow.empress.eco/)
·
[Report Bug](https://github.com/empress-eco/Empress_js_sdk/issues)
·
[Request Feature](https://github.com/empress-eco/Empress_js_sdk/issues)

</div>


## About The Project

Empress JS SDK is a powerful interface that enables effortless communication between your application and a Framework backend. This library simplifies operations like authentication, database manipulation, file upload, and API calls, allowing developers to focus on building the application while the SDK handles backend communication.

### Key Features
- Secure Authentication: Supports login with username and password (cookie based) and token-based authentication.
- Comprehensive Database Operations: Perform CRUD operations and fetch document details effortlessly.
- File Upload Capability: Upload files with ease.
- API Call Support: Make API calls to your Empress backend seamlessly.

The library utilizes the [Axios](https://axios-http.com) library for making API calls to your Empress backend. 

## Technical Stack and Setup Instructions

### Prerequisites
Make sure you have npm installed on your machine. If not, follow the instructions [here](https://nodejs.org/en/download/).

### Installation
Use npm or yarn to install the Empress JS SDK library. Use the following commands to do so:

With npm,
```bash
npm install Empress-js-sdk
```
or with yarn,
```bash
yarn add Empress-js-sdk
```
### Initialization
To get started, initialize the library with your Empress backend's URL:
```js
import { EmpressApp } from 'Empress-js-sdk';
const Empress = new EmpressApp('https://test.Empress.cloud');
```
For token-based authentication, initialize like this:
```js
import { EmpressApp } from "Empress-js-sdk";
const Empress = new EmpressApp("https://test.Empress.cloud", {
    useToken: true,
    token: getTokenFromLocalStorage(),
    type: "Bearer"
})
```

## Usage
For detailed usage instructions and examples, please refer to our [documentation](https://grow.empress.eco/).

## Contribution Guidelines
We welcome and appreciate contributions from the community. Here's how you can contribute:
- Fork the project
- Create your feature branch (`git checkout -b feature/AmazingFeature`)
- Commit your changes (`git commit -m 'Add some AmazingFeature'`)
- Push to the branch (`git push origin feature/AmazingFeature`)
- Open a pull request

## License and Acknowledgements

### License
This project is under the [MIT License](https://github.com/empress-eco/Empress_js_sdk/blob/main/LICENSE). Your contributions are also licensed under the MIT License.

### Acknowledgements
- A big thank you to our maintainers: [Nikhil Kothari](https://github.com/nikkothari22), [Janhvi Patil](https://github.com/janhvipatil), and [Sumit Jain](https://github.com/sumitjain236) for their continuous contributions and support.
- Special thanks to [Axios](https://axios-http.com/) for making our API calls smooth and efficient.
- We are profoundly grateful to the Empress Community, the architects behind the essential tools that power this project. Their innovation and dedication have been instrumental in building the foundations and functionalities we rely on.