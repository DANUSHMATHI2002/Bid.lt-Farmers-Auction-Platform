### 🌾 Bid.it: Direct Agricultural E-Auction & Market Intelligence Platform

**Bid.it** is a full-stack web application developed to decentralize the agricultural supply chain. By providing a direct digital marketplace, it empowers farmers to bypass predatory intermediaries and sell directly to consumers and distributors through a transparent, data-driven bidding system.

---

## 💻 Core Web Features & Utility

### 🕷️ Real-Time Market Scraping & Demand Dashboard

* **Live Price Monitoring:** Integrated logic fetches and displays current market rates for agricultural commodities to ensure transparency.


* **Strategic Pricing Support:** A dedicated "Demand Page" tracks real-time market trends, helping farmers decide the best time to list their produce based on actual demand.


* **Decision Support System:** Farmers can access expert guidance through the interface to help determine fair market values and navigate pricing strategies.



### 🔨 Dynamic E-Auction Engine

* **Live Bidding Mechanism:** A transparent environment where all bids are visible to registered users, and the highest bid updates dynamically in real-time.


* **Shelf-Life Aware Timelines:** The system features conditional logic that sets auction durations based on crop perishability—vegetables are limited to 1-day auctions, while grains like rice and wheat support 3–4 day windows.


* **Automated SMS Notifications:** An integrated gateway sends real-time alerts for outbids, auction wins, and transaction confirmations directly to user mobile numbers.



### 🛍️ Categorized Marketplace

* **Smart Classification:** Listings are organized into intuitive categories, including Vegetables, Fruits, Non-Vegan (livestock), and Farming Equipment.


* **Direct Interaction:** Buyers can browse high-quality product photos, evaluate listings, and submit bids directly to the producer.



---

## 🛡️ Security & Trust Architecture

### 🔐 Verified Identity (Anti-Fraud)

* **Mandatory Authentication:** Access to the selling platform is strictly restricted to users with a verified Farmer ID and a registered phone number.


* **Profile Integrity:** All participants must provide basic details (Name, Address, Contact) to create a traceable and accountable marketplace.



### ⚙️ Transaction & Data Safety

* **Secure Payment Integration:** Supports a wide range of verified payment methods, including BHIM UPI, PhonePe, GPay, and Credit/Debit cards.


* **Relational Data Persistence:** Utilizes a structured MySQL database to maintain a permanent, unalterable audit trail of all bids, user details, and winner declarations.


* **Automated Choice Locking:** Once an auction timeline expires, the system automatically locks the interface, preventing late entries or price manipulation.



---

## 🛠️ Technical Stack

* **Frontend:** HTML5, CSS3, JavaScript, and Bootstrap for a responsive, mobile-friendly interface.


* **Backend:** PHP for robust server-side logic and session management.


* **Database:** MySQL for relational storage and structured data management.


* **Infrastructure:** AWS and Cloudflare for scalable hosting and performance optimization.


* **Workflow:** Integrated API components and CI/CD pipelines for seamless system updates.



---

## 🚀 Setup Instructions

1. **Clone the Repository**:
```bash
git clone https://github.com/DANUSHMATHI2002/Bid-it-Farmer-Auction.git

```


2. **Database Configuration**: Import the provided MySQL schema into your local environment.


3. **Environment Setup**: Update the configuration files with your local server credentials and API keys for the SMS gateway.


4. **Local Deployment**: Run the project via XAMPP/WAMP or a PHP-compatible web server.



---
