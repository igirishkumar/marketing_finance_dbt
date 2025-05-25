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

{% docs customer_id %}
A unique identifier for each user in the system, used across multiple models for tracking user interactions.
{% enddocs %}

{% docs order_id %}
A unique identifier for each order in the system, used across multiple models for tracking user interactions.
{% enddocs %}