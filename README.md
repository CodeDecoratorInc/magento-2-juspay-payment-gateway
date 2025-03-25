# Magento 2 Juspay Payment Gateway

## Introduction
Magento 2 Juspay Payment Gateway extension provides a seamless and secure way to integrate Juspay payment solutions into your Magento 2 store. This extension ensures smooth transactions, enhanced security, and an improved checkout experience. With support for multiple payment methods, it helps in boosting conversions and customer satisfaction.

## How It Works - Magento 2 Juspay Payment Gateway
Magento 2 Juspay Payment Gateway extension enables Magento 2 store owners to integrate Juspay’s payment processing capabilities effortlessly. It provides a streamlined checkout process, ensuring fast and secure transactions. The extension supports multiple payment options, including credit/debit cards, UPI, and net banking, enhancing the flexibility of payment acceptance for merchants.

## Key Features
- **Seamless Juspay Integration** – Easily integrates Juspay with your Magento 2 store.
- **Multiple Payment Methods** – Supports UPI, credit/debit cards, and net banking.
- **Enhanced Security** – Ensures PCI-DSS compliance and secure transactions.
- **Optimized Checkout Experience** – Fast and user-friendly payment processing.

## Juspay Payment Gateway Integration
The Magento 2 Juspay Payment Gateway extension ensures a smooth integration with Magento 2, allowing store owners to accept payments through Juspay effortlessly. It provides a fully optimized checkout experience to reduce cart abandonment and increase sales.

## Multiple Payment Options
Juspay Payment Gateway supports various payment methods such as UPI, credit cards, debit cards, and net banking, offering flexibility and convenience to customers during checkout.

## Secure Transactions
This extension ensures highly secure transactions with PCI-DSS compliance, encryption, and fraud prevention features, safeguarding customer payment data.

## Optimized Performance
With quick response times and efficient payment processing, the extension provides an optimized checkout experience that enhances customer satisfaction and reduces transaction failures.

## Extension Installation
To install the Magento 2 Juspay Payment Gateway extension, use Composer as a dependency management tool.

### Step 1: Install the extension using Composer
```bash
composer require vendor/juspay-payment-gateway
```
For a specific version:
```bash
composer require vendor/juspay-payment-gateway:version
```
**Note:** You may need authentication keys from the vendor or Magento Marketplace.

### Step 2: Run the following Magento commands
```bash
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento setup:static-content:deploy -f
php bin/magento cache:flush
```

## How to Configure Magento 2 Juspay Payment Gateway

### Step 1 - Navigate to Juspay Configuration
1. Log in to your Magento 2 Admin Panel.
2. Go to **Stores** > **Configuration** > **Sales** > **Payment Methods**.
3. Find **Juspay Payment Gateway** and click to expand the settings.

### Step 2 - Enable the Payment Gateway
1. Set **Enable** to "Yes".
2. Enter the **API Key** provided by Juspay.
3. Configure the **Merchant ID** and other necessary credentials.

### Step 3 - Configure Payment Methods
1. Choose the payment methods you want to enable (UPI, Cards, Net Banking).
2. Set transaction settings, including order status and logging options.

### Step 4 - Save Configuration & Test
1. Click **Save Config**.
2. Clear Magento cache using `php bin/magento cache:flush`.
3. Perform a test transaction to verify the setup.

## Download Our [Magento 2 Juspay Payment Gateway](https://codedecorator.com/magento-2-juspay-payment-gateway.html) Extension
