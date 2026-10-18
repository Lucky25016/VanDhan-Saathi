# VanDhan Saathi — System Architecture

## 1. Overview

VanDhan Saathi is a web-based prototype designed to explore
how digital technology can help forest-produce collectors
access product information and organize listings.

The prototype is built using HTML, CSS, and JavaScript.

## 2. Architecture Diagram

```text
+----------------------------------+
|             User                 |
|     Mobile Phone / Computer      |
+----------------+-----------------+
                 |
                 v
+----------------------------------+
|         User Interface            |
|              HTML                |
|      Product Cards and Forms      |
+----------------+-----------------+
                 |
                 v
+----------------------------------+
|          Styling Layer            |
|               CSS                |
|      Layout and Responsive UI     |
+----------------+-----------------+
                 |
                 v
+----------------------------------+
|         Application Logic         |
|           JavaScript              |
|                                  |
|  - Product Search                 |
|  - Category Filtering             |
|  - Form Validation                |
|  - Listing Management             |
+----------------+-----------------+
                 |
                 v
+----------------------------------+
|          Browser Storage           |
|           LocalStorage             |
|                                  |
|  Listings saved in this browser   |
+----------------------------------+

## 3. Technology Stack

| Technology | Purpose |
|------------|---------|
| HTML | Webpage structure |
| CSS | Styling and responsive layout |
| JavaScript | Search, filtering, and listing functions |
| LocalStorage | Saves listings in the current browser |
| GitHub | Source code hosting |
| GitHub Pages | Website hosting |

## 4. Main Components

### Product Catalogue
Displays examples of forest produce, including Mahua Flowers,
Tamarind, Forest Honey, Sal Leaves, and Harra.

### Search and Filters
Helps users search for products and filter them by category.

### Price Guide
Displays illustrative demo prices. These are not verified
market prices.

### Listing Form
Allows users to enter forest-produce listing information.

### Browser Storage
Stores listings in the current browser. These listings are
not automatically shared with other users or devices.

## 5. Data Flow

1. The user opens the website.
2. The browser loads the HTML, CSS, and JavaScript.
3. JavaScript handles product search and filtering.
4. The user enters listing information.
5. Supported listing data is saved in browser LocalStorage.
6. Saved listings can be viewed again in the same browser.

## 6. Current Limitations

- No backend server is connected.
- No shared online database is implemented.
- Listings are not automatically shared between users.
- No live market-price service is connected.
- Buyer and seller accounts are not implemented.
- Real buyer connections and transactions are not supported.

## 7. Future Improvements

- Add a backend and shared database.
- Introduce buyer and seller accounts.
- Integrate reliable market-price information.
- Add support for local languages.
- Explore location-based market information.
- Test the application with intended users.

## 8. Conclusion

VanDhan Saathi is an initial prototype exploring how a
simple web application could support rural livelihoods
through better access to forest-produce information.

Further development and real-world testing would be needed
to evaluate its effectiveness.
