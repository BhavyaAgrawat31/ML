### Task 19: Initial Data Dictionary

| Table | Column | Data Type | Description | Example Value |
|---|---|---|---|---|
| customers | customer_id | String | Unique identifier for an order-level customer record | abc123 |
| customers | customer_unique_id | String | Unique identifier for a customer | abc123 |
| customers | customer_city | String | City of the customer | sao paulo |
| customers | customer_state | String | State of the customer | SP |
| orders | order_id | String | Unique identifier for an order | xyz789 |
| orders | customer_id | String | Identifier linking the order to a customer | abc123 |
| orders | order_status | String | Current status of the order | delivered |
| orders | order_purchase_timestamp | Date/Time | Date and time when the order was placed | 2017-10-02 10:56:33 |
| order_items | order_id | String | Identifier linking the item to an order | xyz789 |
| order_items | order_item_id | Integer | Sequential item number within an order | 1 |
| order_items | product_id | String | Identifier of the purchased product | abc123 |
| order_items | seller_id | String | Identifier of the seller | xyz789 |
| order_items | price | Float | Price of the product | 59.90 |
| order_items | freight_value | Float | Freight/shipping cost for the item | 13.29 |
