Sale Supply Module
##################

The Sale Supply module adds a supply on sale option on product.
If checked, it will generate a purchase request for each sale line of this
product regardless of the stock levels. Once the purchased products are
received they are assigned on the customer shipments.

.. warning::
    If the shiment method is *On Invoice Paid*, the purchase request will be
    created only when all the invoice lines are paid
..
