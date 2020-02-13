================================================
Invoice based on delivered or ordered quantities
================================================

Depending on your business, you have two options for invoicing:

- **Invoice what is ordered**: invoice the full order as soon as the sales order is confirmed.

- **Invoice what is delivered**: invoice the delivered quantity as soon as a quantity has been
  successfully delivered.

The **Invoice what is ordered** rule is used as the **default mode** in Odoo Sales.

.. note::
   The benefits of using the **Invoice what is delivered** rule concern businesses that sell
   materials, liquids or food in large quantities. In these cases, the quantity might diverge a
   little bit and it is, therefore, preferable to invoice the quantity actually delivered.

Activate these features
=======================

To choose the best option for your business, you will have to go to :menuselection:`Sales -->
Configuration --> Settings` and under the invoicing category, you will find the **Invoicing policy**
where you will have the possibility to choose the rule you want to apply.

.. image:: media/invoicing_policy_1.png
   :align: center
   :class: img-thumbnail
   :alt: How to choose your invoicing policy on Odoo Sales?

.. important::
   If you decide to choose the **Invoice what is delivered** rule, it will not be possible to
   activate the **Automatic invoice** feature which automatically generates an invoice when the
   online payment is confirmed.

Choose an invoicing policy on a product form
============================================

From any product page, under the **Sales tab**, you will find the invoicing policy and you will
have the possibility to change it manually.

.. image:: media/invoicing_policy_2.png
   :align: center
   :class: img-thumbnail
   :alt: How to change your invoicing policy on a product form on Odoo Sales?

Impact on sales flow
====================

On Odoo Sales, the basic sales flow will be to create a quotation, send it to your customer,
wait for confirmation, confirm the sales order and create an invoice.

- **Invoice what is ordered**: No impact on this basic sales flow. indeed, you can invoice as soon
  as the sale is confirmed.

- **Invoice what is delivered**: Small impact on sales flow because you will have to install the
  **Inventory App** to confirm the delivered quantity before creating an invoice with the
  **Sales App**. Indeed, if you try to create an invoice without validating the delivered quantity,
  you will receive an error message as below.

  .. image:: media/invoicing_policy_3.png
     :class: img-thumbnail
     :alt: How the choice of your invoicing policy impacts your sales flow on Odoo Sales?

.. note::
   Once the quotation is confirmed and that the status went from **Quotation sent** to
   **Sales order**, you are able to see your delivered and invoiced quantities directly from your
   sales order (it is true for both rules).

   .. image:: media/invoicing_policy_4.png
      :align: center
      :class: img-thumbnail
      :alt: How to see your delivered and invoiced quantities on Odoo Sales?

   Odoo will automatically add the quantities to the invoice (even if it is a partial delivery).

Finally, to create an invoice, you will have different possibilities: regular invoice,
down payment (percentage) and down payment (fixed amount) as you can see below.

.. important::
   Be sure to check out our documentation about down payment here: :doc:`down_payment`, to master
   this incredible feature.

.. seealso::
   - :doc:`down_payment`