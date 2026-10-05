### Task 19: Initial Data Dictionary

| Table | Column | Data Type | Description | Example Value |
|---|---|---|---|---|
| customers | customer_id | String | Unique identifier for an order-level customer record | abc123 |
| customers | customer_unique_id | String | Unique identifier for a customer | abc123 |
| customers | customer_zip_code_prefix | Integer | First five digits of the customer's ZIP code | 14409 |
| customers | customer_city | String | City of the customer | sao paulo |
| customers | customer_state | String | State of the customer | SP |
| orders | order_id | String | Unique identifier for an order | xyz789 |
| orders | customer_id | String | Identifier linking the order to a customer | abc123 |
| orders | order_status | String | Current status of the order | delivered |
| orders | order_purchase_timestamp | Date/Time | Date and time when the order was placed | 2017-10-02 10:56:33 |
| orders | order_approved_at | Date/Time | Date and time when the order was approved | 2017-10-02 11:07:15 |
| orders | order_delivered_carrier_date | Date/Time | Date when the order was handed to the carrier | 2017-10-04 15:30:00 |
| orders | order_delivered_customer_date | Date/Time | Date when the order was delivered to the customer | 2017-10-10 18:20:00 |
| orders | order_estimated_delivery_date | Date/Time | Estimated delivery date of the order | 2017-10-18 00:00:00 |
| order_items | order_id | String | Identifier linking the item to an order | xyz789 |
| order_items | order_item_id | Integer | Sequential item number within an order | 1 |
| order_items | product_id | String | Identifier of the purchased product | abc123 |
| order_items | seller_id | String | Identifier of the seller | xyz789 |
| order_items | shipping_limit_date | Date/Time | Deadline for the seller to ship the item | 2017-10-06 11:07:15 |
| order_items | price | Float | Price of the product | 59.90 |
| order_items | freight_value | Float | Freight/shipping cost for the item | 13.29 |
| order_payments | order_id | String | Identifier linking the payment to an order | xyz789 |
| order_payments | payment_sequential | Integer | Sequence number of the payment for an order | 1 |
| order_payments | payment_type | String | Type of payment used | credit_card |
| order_payments | payment_installments | Integer | Number of installments used for payment | 2 |
| order_payments | payment_value | Float | Value of the payment | 72.19 |
| order_reviews | review_id | String | Unique identifier of the review | review123 |
| order_reviews | order_id | String | Identifier linking the review to an order | xyz789 |
| order_reviews | review_score | Integer | Score given by the customer | 5 |
| order_reviews | review_comment_title | String | Title of the customer's review | Great product |
| order_reviews | review_comment_message | String | Message or content of the customer's review | Very good quality |
| order_reviews | review_creation_date | Date/Time | Date when the review was created | 2018-01-15 00:00:00 |
| order_reviews | review_answer_timestamp | Date/Time | Date and time when the review was answered | 2018-01-16 10:30:00 |
| products | product_id | String | Unique identifier of the product | abc123 |
| products | product_category_name | String | Category of the product | beleza_saude |
| products | product_name_lenght | Integer | Number of characters in the product name | 40 |
| products | product_description_lenght | Integer | Number of characters in the product description | 500 |
| products | product_photos_qty | Integer | Number of photos available for the product | 3 |
| products | product_weight_g | Float | Weight of the product in grams | 500.0 |
| products | product_length_cm | Float | Length of the product in centimeters | 20.0 |
| products | product_height_cm | Float | Height of the product in centimeters | 10.0 |
| products | product_width_cm | Float | Width of the product in centimeters | 15.0 |
| sellers | seller_id | String | Unique identifier of the seller | xyz789 |
| sellers | seller_zip_code_prefix | Integer | First five digits of the seller's ZIP code | 13023 |
| sellers | seller_city | String | City of the seller | campinas |
| sellers | seller_state | String | State of the seller | SP |
| geolocation | geolocation_zip_code_prefix | Integer | ZIP code prefix associated with the location | 01001 |
| geolocation | geolocation_lat | Float | Latitude of the location | -23.5505 |
| geolocation | geolocation_lng | Float | Longitude of the location | -46.6333 |
| geolocation | geolocation_city | String | City associated with the location | sao paulo |
| geolocation | geolocation_state | String | State associated with the location | SP |
| product_category_name_translation | product_category_name | String | Product category name in Portuguese | beleza_saude |
| product_category_name_translation | product_category_name_english | String | English translation of the product category | health_beauty |