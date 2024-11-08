# ArtStore: Web-Based Art Reproduction Sales System

## Project Overview
**ArtStore** is an online platform for buying and selling art reproductions. It is designed to connect art lovers with a diverse collection of high-quality reproductions while providing artists and galleries with an additional sales channel. ArtStore aims to offer a seamless and secure shopping experience with a user-friendly interface, efficient management tools for administrators, and robust security features.

## Key Features
- **User Registration and Authentication**: Secure sign-up, login, and profile management for customers and administrators.
- **Product Management**: Admins can add, edit, or remove products and organize them by category.
- **Product Browsing and Search**: Users can browse art collections by categories or search for specific pieces.
- **Cart and Checkout System**: Add items to a shopping cart and proceed to secure checkout with payment options.
- **Order Management**: Track and view order history for both users and administrators.
- **Sales Reporting**: Generate and view reports for analyzing sales trends and product performance.
- **Secure Payment Integration**: Support for payment gateways to handle transactions securely.
  
## Technology Stack
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP (Laravel/CodeIgniter framework preferred)
- **Database**: MySQL
- **Tools and Libraries**: Bootstrap for UI design, AJAX for dynamic content loading
- **Environment**: LAMP stack (Linux, Apache, MySQL, PHP)

Based on the project structure you've provided, here's a summary of the directory layout and a brief explanation for each key section in the ArtStore project.

---

## Project Structure

```
D:\PROJECT\PHP\ArtStore\ARTSTORE\artstore\
├── images\                     # Image assets for the website
│   ├── artists\                # Images related to artists
│   ├── genres\                 # Images representing different art genres
│   ├── works\                  # Images of art works
│   ├── background.gif          # Background image for the site
│   └── logo.ico                # Website icon
├── nbproject\                  # NetBeans project files
│   ├── private\                # Private project configurations
│   ├── project.properties      # Project properties configuration
│   └── project.xml             # Project configuration file in XML
├── aboutus.php                 # Page describing information about ArtStore
├── artist.php                  # Page displaying information about artists
├── artistdal.php               # Data Access Layer (DAL) for managing artist data
├── artwork.php                 # Page displaying artwork details
├── cartdal.php                 # DAL for managing shopping cart data
├── configinc.php               # Configuration file, likely for database and global settings
├── custdal.php                 # DAL for managing customer data
├── custlogin.php               # Customer login page
├── custlogout.php              # Customer logout page
├── custreg.php                 # Customer registration page
├── gallery.php                 # Page displaying a gallery of artworks
├── genredal.php                # DAL for managing genres data
├── genres.php                  # Page displaying art genres
├── index.php                   # Main entry point for the ArtStore site
├── list.txt                    # Text file, possibly containing initial data or notes
├── mysqlinc.php                # MySQL database connection and initialization
├── smplsearch.php              # Simple search functionality page
├── subjects.php                # Page displaying art subjects
├── viewcart.php                # Page for viewing items in the shopping cart
├── viewcustaccount.php         # Page for viewing and managing customer account details
└── worksdal.php                # DAL for managing artwork data
```

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Anueen/ArtStore.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd ArtStore
   ```
3. **Setup the Database**:
   - Create a MySQL database for the project.
   - Import the SQL dump file (`art.sql`) located in the `database/` folder.

4. **Configure Environment Variables**:
   - Rename `.env.example` to `.env` and update database credentials.
   - Set up any API keys for payment integration (e.g., Stripe or PayPal).

5. **Start the Local Server**:
   ```bash
   php artisan serve
   ```
6. **Access the Platform**:
   - Open your browser and go to `http://localhost:8000`.

## Usage
1. **Sign Up / Log In**:
   - Register as a new user or log in as an admin to manage products.
2. **Browse Products**:
   - Browse and search for art reproductions by category or keyword.
3. **Add to Cart and Checkout**:
   - Add items to your cart and proceed to checkout.
4. **Order Management**:
   - Track orders, view order history, and admins can generate reports.

## Contributors
- **Anurag kohli** - Project Lead, Backend Developer, Frontend Developer,Database Administrator

## License
This project is licensed under the MIT License.

## Contact
For questions, feedback, or suggestions, please reach out to:
- **Email**: anuragkohlicu@gmail.com
- **GitHub**: [https://github.com/Anueen]
---
