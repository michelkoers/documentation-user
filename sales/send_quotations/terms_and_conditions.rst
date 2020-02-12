================================
Add terms & conditions on orders
================================

Specifying terms and conditions is essential to set out important contractual points such as payment
terms, limitation of liability and delivery terms between customers and sellers. Every seller must
declare all formal information concerning products and company policy. But, in the meantime, each
customer must take note of all these conditions before committing to anything. With Odoo Sales, it
is very easy to include your default terms and conditions on every quotation, sales order and
invoice that you manage.

Enable this feature
===================

Go to :menuselection:`Invoicing --> Configuration --> Settings` and activate **Default Terms &
Conditions** under the **Customer Invoices** category.

.. image:: media/terms_conditions_1.png
   :align: center
   :class: img-thumbnail
   :alt: How to enable default terms & conditions on Odoo Sales?
 
.. note::
   Please note that this feature is activated via the settings of the **Invoicing App** and **not**
   via the settings of the **Sales App**. More than that, you don't need to install the invoicing
   application because it will automatically be done with the installation of the sales application.

Add terms & conditions to your quotations, sales orders and invoices
====================================================================

In the settings of the **Invoicing App**, you will have the possibility to insert your default terms
and conditions.

.. image:: media/terms_conditions_2.png
   :align: center
   :class: img-thumbnail
   :alt: Default terms & conditions on quotation on Odoo Sales?

They will appear subsequently on every quotation, sales order and invoice.

Add terms & conditions to your quotation templates
==================================================

For even more convenience, you can specify your terms & conditions on every quotation templates
that you create. These conditions will only appear if you choose to use a distinct quotation
template when creating a quotation.

.. image:: media/terms_conditions_3.png
   :align: center
   :class: img-thumbnail
   :alt: Add terms & conditions to your quotation templates on Odoo Sales?

.. important::
   Be sure to check out our documentation about quotation templates: :doc:`quote_template`,
   to master each step of this amazing feature.
  
Add more detailed terms & conditions
====================================

Here are different ideas to share more details about your terms & conditions with your customers:

- Use the **Website App** and create your own terms & conditions page to which you can refer.
  For example, here is the Odoo terms & conditions page that we send to our customers:

  .. image:: media/terms_conditions_4.png
     :class: img-thumbnail
     :alt: Terms & conditions on your website?

- Attach an external document with more detailed conditions when you are about to send your
  quotation by email to your customers.

  .. image:: media/terms_conditions_5.png
     :class: img-thumbnail
     :alt: Terms & conditions in attachments in your email?

- Create and edit email templates to set a default attachment for all quotation emails that you
  will send in the future. To do so, you have to go to :menuselection:`Sales --> Configuration
  --> Quotation templates` and create a new quotation template or modify an existing one. You
  will see that under the confirmation tab, you will be able to activate online signatures, online
  payments and to set a confirmation mail in which you will have the possibility to configure
  the default attachment. There, you can put your detailed terms & conditions.

  .. image:: media/terms_conditions_6.png
     :class: img-thumbnail
     :alt: Terms & conditions in attachments in your quotation template?

.. tip::
   This option is possible in **Developer mode** in Odoo. To customize your email templates you can
   go to :menuselection:`Settings --> Technical --> Email --> Templates`.

With Odoo Sales it is now very simple to deal with terms & conditions.

.. seealso::
   - :doc:`quote_template`
   - :doc:`get_signature_to_validate`
   - :doc:`get_paid_to_validate`
