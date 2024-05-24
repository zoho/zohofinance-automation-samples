# zohofinance-automation-samples
A sample collection of custom functions to demonstrate the automation workflow in Zoho Books, a comprehensive cloud accounting platform that takes care of your business finance.

Every business is unique and each of them follows a specific workflow. While managing your customers' transactions with Zoho, you might have some needs unique to your business. Custom Functions help you address such needs. Here we have compiled a set of custom functions that address different needs.

## Custom Functions - Setup
- In Zoho Books [*Web app*](https://books.zoho.com/), navigate to Settings -> Automation -> Custom Functions.
- Create a new Custom function and provide a suitable name for it.
- Choose the corresponding module and appropriate event to trigger the custom function.
- Copy the required code depending on your use case.
- Customize the code according to your requirements (if needed).
- Save the Custom function and you are good to go.

## Custom Functions
1. [*Convert Estimate to Sales Order Automatically*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/convert_estimate_to_salesorder_automatically.ds)
2. [*Create a Deal in Zoho CRM when Estimate is created in Zoho Books*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/create_deal_from_estimate_automatically.ds)
3. [*Make Reporting Tags mandatory in Zoho Books*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/make_reporting_tags_mandatory.ds)
4. [*Schedule Customer Statement in Zoho Books*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/schedule_customer_statement.ds)
5. [*Add Late fee by creating a New Invoice in Zoho Books*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/late_fee_add_a_new_invoice.ds)
6. [*Calculate Commission for SalesPerson and add it as Expense in Zoho Books*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/calculate_salesperson_commission_and_create_expense.ds)
7. [*Fetch Deals field value from Zoho CRM to related Estimates in Zoho Books*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/fetch_deals_field_value_in_related_estimates.ds)
8. [*Add Additional Charges to Invoices in Zoho Books*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/add_additional_charges_to_invoice.ds)
9. [*Carry forward attachments from Sales order to Purchase order in Zoho Books*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/carry_forward_attachments_so_to_po.ds)
10. a)[*Update Cost Price of an Item based on the value in the Bill in Zoho Books*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/update_cost_price_during_bill_creation.ds)

    b)[*Update Selling Price of an Item based on the value in the Invoice in Zoho Books*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/update_selling_price_during_invoice_creation.ds)
11. [*Apply unused credits automatically to Invoice when created in Zoho Books*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/apply_unused_credits_to_invoice.ds)
12. [*Auto Approve Purchase Order when total less than or equal to 1000 in Zoho Books*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/auto_approve_po.ds)
13. [*To Calculate Margin at transaction level*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/transaction_level_margin.ds)
14. [*To send draft invoices to Cliq channel*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/draft_invoices_to_cliq.ds)
15. [*Calculate related Sales Orders' shipping charge and add it to Invoice*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/calculate_total_shipping_charges.ds)
16. [*To Fetch attachment from Bill To Invoice*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/Fetch-attachment-from-Bill-to-Invoice.ds)
17. [*To assign Account owner with Zoho Books Contact owner*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/Assign-Account-owner-with-ZohoBooks-Contact-Owner.ds)
18. [*Associate the templates automatically based on customer language*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/associate_template.ds)
19. [*Associate the templates automatically based on branch*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/branch_based_template.ds)
20. [*Custom calculation in item table of invoices*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/Custom_Calculation.ds)
21. [*To send unpaid invoices[consolidated] to customers*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/send_unpaidinvoices%5Bconsolidated%5D_to_customers.ds)
22. [*To automatically associated Sales Person*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/associate_salesperson.ds)
23. [*To remove discount when an invoice is over due*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/remove_discount.ds)
24. [*To populate deal name on Estimate PDF*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/populate-deal-name-on-PDF.ds)
25. [*To create PO From SO(based on Preferred vendor)*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/Create-PO-From-SO.ds)
26. [*Update deal stage*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/update-deal-stage.ds)
27. [*Apply Unused credits to bills*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/apply_unused_credits_to_bills.ds)
28. [*Loyalty Point*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/loyalty_point.ds)
29. [*Update Expiry Date of an Estimate*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/update_expiry_date.ds)
30. [*To show the associated Purchase Orders in Sales Order*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/populate_associated_po.ds)
31. [*Product Warrenty Calculation*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/product_%20warranty.ds)
32. [*To Schedule an email for low-stock Items*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/schedule_email_for_low_stock_items.ds)
33. [*Associate the templates automatically based on customer Country*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/country_based_template.ds)
34. [*To add Gift Item for An invoice*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/to_add_gift_items.ds)
35. [*To create a task when an estimate is created*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/create_task.ds)
36. [*To send Item Catalogue to Customers*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/send_item_catalogue.ds)
37. [*Display List Of Associated SO on Estimate details screen*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/display_associated_so.ds)
38. [*To Add Rush charges on Invoices*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/rush_charge.ds)
39. [*Schedule Vendor Statement*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/schedule_vendor_statement.ds)
40. [*Credit_Limit_Alert_For_Invoice*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/credit_limit_alert.ds)
41. [*Credit Limit Alert for Sales Order*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/credit_alert_for_so.ds)
42. [*To show the actual Rate of Items on the Invoice*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/show_actual_rate.ds)
43. [*To enable client portal*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/enable_client_portal.ds)
44. [*To schedule an email if the closing balance of the account is higher than the soft limit*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/account_notification.ds)
45. [*To send an email when exceeds the Safe Limits of an account*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/account_safe_limit_notification.ds)
46. [*Create an Invoice From Billable Expense*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/create_invoice_from_billable_expense.ds)
47. [*To send list of lapsed customers to users*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/lapsed_customers.ds)
48. [*To synchronize the custom field from Zoho Expense with Zoho Books.*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/sync_custom_field_from_ZE_to_ZB.ds)
49. To manage Fixed installment payments Script for invoice

    a)[*Script for invoice*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/manage_emi.ds)

    b)[*script For Retainer Invoice*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/manage_emi_retainer_invoice.ds)
50. To manage Fixed installment payments Script for invoice using Custom Button.

    a)[*Custom Button Script*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/manageEmi_button.ds)

    b)[*Related List Script*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/manageEmi_relatedList.ds)
51. [*Send Bulk Email From Zoho Books*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/bulk_email.ds)
52. [*Transaction level profitability for Quotes*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/quotes_transaction_level_profitability.ds)
53. [*Price List based on Currency*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/pricelist_based_on_currency.ds)
54. [*Transaction level profitability for Invoices*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/transaction_level_profitability_invoices.ds)
55. [*Creation time of invoice on PDF*](https://github.com/zoho/zohofinance-automation-samples/blob/main/CustomFunctions/created_timeOn_pdf.ds)

