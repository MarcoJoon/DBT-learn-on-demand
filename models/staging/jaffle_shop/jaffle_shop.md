{% docs order_status %}
	
One of the following values: 

| status         | definition                                       |
|----------------|--------------------------------------------------|
| placed         | Order placed, not yet shipped                    |
| shipped        | Order has been shipped, not yet been delivered   |
| completed      | Order has been received by customers             |
| return pending | Customer indicated they want to return this item |
| returned       | Item has been returned                           |

{% enddocs %}

{% docs payment_status %}
	
One of the following values: 

| status         | definition                                       |
|----------------|--------------------------------------------------|
| success        | Payment completed successfully                   |
| fail           | Payment failed                                   |

{% enddocs %}

{% docs payment_method %}
	
One of the following values: 

| status         | definition                                       |
|----------------|--------------------------------------------------|
| credit card    | Credit card was used to process payment          |
| bank transfer  | Bank transfer was used to process payment        |
| coupon         | Coupon was used to process payment               |
| gift card      | Gift card was used to process payment            |

{% enddocs %}