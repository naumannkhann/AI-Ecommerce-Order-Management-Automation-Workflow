# AI-Ecommerce-Order-Management-Automation-Workflow #

An end-to-end e-commerce order management automation system.
Tech Stack Used:
*Lovable – E-commerce website.
*Supabase (PostgreSQL) – Order storage & status management.
*n8n – Workflow automation.
*Google Forms & Sheets – Customer & courier confirmations.
*Payment Method: Cash on Delivery (COD).

How the System Works:
*Orders are placed on the website and stored in Supabase with Pending status.
*Customers receive an email to confirm their order.
*If not confirmed → status changes to Cancelled.
*If confirmed → status updates to Confirmed.
*Courier receives delivery request via email.
*Delivered → status becomes Delivered.
*Returned → status becomes Returned.

The workflows are currently triggered manually for testing, but the same logic can be upgraded to webhook-based production automation.
