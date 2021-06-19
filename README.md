# wooSample

## Order Sample
```javascript
let orderData = {
  "id": 3037, // Unique Order ID
  "currency": "INR",
  "discount_tax": "0",
  "discount_total": "16.5",
  "shipping_tax": "0",
  "shipping_total": "0.00",
  "subtotal": 504.29,
  "total": "528.50",
  "total_discount": 16.5,
  "total_tax": "40.71",
  "item_count": 3,
  "coupon_codes": [
    "firstbuy"
  ],
  "shipping_method": "Free shipping",
  "order_date": "2021-06-19 06:53:38",
  "status": "processing", // Curreny Order Status [pending, processing, completed, cancelled, refunded, failed, dispatched, on-hold]
  "items": [
    {
      "posify_product_id": 0, // Posify product ID
      "product_id": 2596,
      "variation_id": 0,
      "product_name": "Peri Peri Chicken Seekh Kebab",
      "quantity": 1,
      "subtotal": "339.285714",
      "total": "339.285714",
      "subtotal_tax": "40.71",
      "tax_class": "12-tax",
      "tax_status": "taxable",
      "type": "line_item"
    },
    {
      "posify_product_id": 0, // Posify product ID
      "product_id": 2596,
      "variation_id": 0,
      "product_name": "Peri Peri Chicken Seekh Kebab",
      "quantity": 1,
      "subtotal": "0",
      "total": "0",
      "subtotal_tax": "0",
      "tax_class": "12-tax",
      "tax_status": "taxable",
      "type": "line_item"
    },
    {
      "posify_product_id": 0, // Posify product ID
      "product_id": 563,
      "variation_id": 0,
      "product_name": "Chicken Seekh Kebab",
      "quantity": 1,
      "subtotal": "165",
      "total": "148.5",
      "subtotal_tax": "0",
      "tax_class": "",
      "tax_status": "taxable",
      "type": "line_item"
    }
  ],
  "customer": {
    "customer_ip_address": "127.0.0.1", 
    "customer_note": "Test order", // This is order note comes from customer while placing the order.
    "billing": {
      "billing_first_name": "NexGen",
      "billing_last_name": "Team",
      "billing_company": "",
      "billing_address_1": "Dwarka mor",
      "billing_address_2": "Line 2 address",
      "billing_city": "New Delhi",
      "billing_state": "DL",
      "billing_postcode": "110059",
      "billing_country": "IN",
      "billing_email": "support@nexgi.com",
      "billing_phone": "7835851117"
    },
    "shipping": {
      "shipping_first_name": "NexGen",
      "shipping_last_name": "Team",
      "shipping_company": "",
      "shipping_address_1": "Dwarka mor",
      "shipping_address_2": "Line 2 address",
      "shipping_city": "New Delhi",
      "shipping_state": "DL",
      "shipping_postcode": "110059",
      "shipping_country": "IN"
    }
  }
}
```
