# bigcommerce-products-connector
BigCommerce Product Connector 

##### bigcommerce-data-connector

# Product Description & Purpose

BigCommerce is an e-commerce platform that provides online store creation, search engine optimization, website hosting, marketing, and security services to businesses of all sizes. 

The BigCommerce Product Data Connector pulls product data such as product details, pricing, availability status, and images from your BigCommerce product catalog into Yext to power rich customer experiences with Yext Search and Pages. This app keeps your product catalog up to date, and any changes made to your product data in BigCommerce will sync automatically to the Yext Knowledge Graph once you set up webhooks. All built-in configuration is customizable post-installation. In order to install this app, you will need a BigCommerce account and a Yext account.

This app creates the following custom connectors:	

- bigCommerce\_ProductsConnector

This app creates the following custom fields:

- bigCommerce\_availabilityStatus
- bigCommerce\_freeShippingStatus
- bigCommerce\_productCategory
- bigCommerce\_productType
- bigCommerce\_reviewsCount
- bigCommerce\_reviewsRatingSum
- bigCommerce\_salePrice


# Requirements

To use this app you will need to have done the following before you install:

- Have created a custom app in your BigCommerce store.
- Generated and have access to your BigCommerce API Access Token, Client ID, Client Secret, and store hash. 


### Authentication

Follow the step-by-step instructions below to install the BigCommerce Product Connector app.

# How to Install

If you are an existing Yext customer, you can install the  BigCommerce Product Connector here <https://www.yext.com/s/me/apps/1002832>

If you are currently using a Yext sandbox account, you can install the BigCommerce Product Connector here <https://sandbox.yext.com/s/me/apps/1004442>.

If you are not an existing customer, but interested in learning more, try out a free trial here for a production account, or sign up for Hitchhikers and get started with a sandbox account, here <https://hitchhikers.yext.com/>. 

Install the connector to begin pulling your BigCommerce data into your Knowledge Graph! All you have to do is create a custom API account in BigCommerce in order to give Yext permission to access your personal BigCommerce store.

### Note:

Follow the below steps to create a custom API account in BigCommerce:
Login to your BigCommerce store. Navigate to **Settings > API > API Accounts**.
Click **Create API account** and select V2/V3 API Token as the “Token type.”  Give this app a name in the field below. 
Under “OAuth scopes,” select **read-only** next to “Products.” You can leave all other scopes set to **None**. 
Click **Save**.  Once you do so, a pop up will appear with your BigCommerce API Credentials, and a .txt file will automatically download to your computer. 
Make sure to **save the .txt file or copy the Client ID, Client Secret, and Access Token** that have been generated for you. You won’t be able to access this information later, and you will need to input it when you install the BigCommerce Data Connector app in the Yext App Directory. If you lose these credentials, you will need to follow steps 1-5 again to create a new API account.  
Click **Done**. 


### To install the BigCommerce Product Connector:

- Navigate to **Apps > Directory** and search for the BigCommerce Product Connector app.
- Review the app details and click **Install.**
- Allow the connector to access your Yext Account by clicking **Next.**
- Input the necessary information:
    - **Access Token:** Generated in the .txt file you generated when you created the BigCommerce app. 
    - **Store Hash:** Generated in the .txt file you saved when you created the BigCommerce app. This is the 10-character string contained in the API Path URL. Example: https://api.bigcommerce.com/stores/YOUR-STORE-HASH/v3/
    - **Sale Price Currency:** Input the currency code your sale prices should be displayed in (USD, EUR, INR, etc.).   
    - **Store Name:** The name of your store can be found at the beginning of your storefront URL. 
    - ** Example: https://YOUR-STORE-NAME.mybigcommerce.com/ (you do not need to include “my.bigcommerce.com”, just your store name). 
    - **Retail Price Currency:** Input the currency your retail (regular) prices should be displayed in (USD, EUR, INR, etc.). 
- Click **Authorize,** which will install and run the connector.
- You will be redirected to the BigCommerce Product Connector overview page.
- Click **Run Connector** to pull in all of your products. 
- Check out the newly created Product entities in your Knowledge Graph!
