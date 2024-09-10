# QuickBite

QuickBite is a convenient and efficient food  application designed to simplify your dining experience, where users can submit, share, and review receipes. and managing your food preferences all in one place.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **User-Friendly Interface**: Easy navigation and a clean UI for a smooth user experience.
- **Menu Browsing**: Browse menus with a variety of cuisines.
- **Multi-Platform**: Available on web and mobile devices for flexibility and convenience.

## Demo

<img width="1387" alt="Screenshot 2024-09-11 at 02 47 21" src="https://github.com/user-attachments/assets/c1c3d5a5-444f-4f7f-ba62-8c03eab41ad4">


<img width="1365" alt="Screenshot 2024-09-11 at 02 47 43" src="https://github.com/user-attachments/assets/bbbc8383-1039-43f9-8049-ceaea7025972">


<img width="1358" alt="Screenshot 2024-09-11 at 02 48 02" src="https://github.com/user-attachments/assets/ae72f4c7-6454-4765-955e-ae1db05042d1">


<img width="1276" alt="Screenshot 2024-09-11 at 02 48 13" src="https://github.com/user-attachments/assets/8dc488bd-054b-4e97-a79c-443ef1e46c0b">


<img width="1238" alt="Screenshot 2024-09-11 at 02 48 30" src="https://github.com/user-attachments/assets/f41c0adb-aa22-46d8-b162-646221203a0f">


## Installation

To get a local copy of QuickBite up and running, follow these steps:

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/)
- [MongoDB](https://www.mongodb.com/) (for backend database)

### Steps

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Partha02Bh/QuickBite.git
    ```
2. **Navigate to the project directory**:
    ```bash
    cd QuickBite
    ```
3. **Install dependencies**:
    ```bash
    npm install
    ```
4. **Set up environment variables**:

    Create a `.env` file in the root directory and add your configuration settings. For example:

    ```plaintext
    PORT=5000
    MONGO_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    ```

5. **Start the application**:

    For development:
    ```bash
    npm run dev
    ```

    For production:
    ```bash
    npm start
    ```

6. **Access the application**:

    Open your browser and visit `http://localhost:5000`.

## Usage

1. **Browse Restaurants**: View a list of available restaurants near you.
2. **View Menus**: Click on a restaurant to view its menu.
3. **Place an Order**: Add items to your cart, customize your order, and proceed to checkout.
4. **Track Your Order**: Receive updates on your order status from preparation to delivery.

## Configuration

- **Database**: Make sure your Sqlite3 instance is running and correctly set in your `.env` file.
- **API Keys**: Add any required API keys (e.g., for payment processing) in your `.env` file.

## Technologies Used

- **Frontend**: React, Redux, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: Sqlite3


## Contributing

Contributions are welcome! Follow these steps to contribute:

1. Fork the project.
2. Create your feature branch:
    ```bash
    git checkout -b feature/AmazingFeature
    ```
3. Commit your changes:
    ```bash
    git commit -m 'Add some AmazingFeature'
    ```
4. Push to the branch:
    ```bash
    git push origin feature/AmazingFeature
    ```
5. Open a pull request.

Please ensure your code adheres to the project's coding standards and conventions.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Partha02Bh - [LinkedIn](https://www.linkedin.com/in/parthasarathi-bhattacharya-0643b1213/) - [Email](mailto:your-email@example.com)

Project Link: [https://github.com/Partha02Bh/QuickBite](https://github.com/Partha02Bh/QuickBite)
