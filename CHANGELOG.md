# Changelog
## [5.3.0] - 2020-02-25
## Features
- Add Pack Feature in sale order.(__parent__)
- Remove Pack Feature from Product.
- FLEET: Manage rental cars and minor fixes.
- Studio: New features - Label with color, multiline string, grid column sequence, form width, spacer and order by properties.
- Add DMS Import.
- FORECAST RECAP LINE TYPE : create new object ForecastRecapLineType
- JSON-MODEL-FORM : add tracking on json fields
- Export studio app: email action - email template
- Export Studio app: export actions created with meta-action-from
- STOCK RULE: New boolean alert when orderAlertSelect is not alert and stockRuleMessageTemplate added.
- Studio : Added validIf property for custom field.
- Studio: MetaAction and MetaSelect menus with group by on app.
- META-MODEL-FORM: add tracking on json fields.
- CITY: Import automatically from Geonames files.
- MRP: Freeze proposals after manually modifying them.
- Added a global configuration to base app to define number of digits for quantity fields.
- Address: Addition of boolean 'isSharedAddress' in base config to check addresses are shared or not.
- BANK STATEMENT LINE: order by operation date and sequence in AFB120 grid view.
- BANK DETAILS: add search button on bank-details-bank-order-company-grid.

## Improvements
- JOURNAL: new viewer to display the balance.
- SALE ORDER LINE: Display availability status on sale order line grid view if sale order status is 'Confirmed'.
- Map: Filter out the data with empty address.
- Studio: sidebar option for panel.
- Studio: Tab display for panel tab.
- Studio: group by application on json model grid view.
- JSON FIELD FORM: add tracking in form fields.
- ExtraHoursLine: Add new field 'Type' referencing new domain ExtraHoursType.
- Account: Remove DirectDebitManagement.
- MENU BUILDER: Add selection support for icon and iconBackground.
- Custom Model: Hide menu panel and allows to create menu from menubuilder only.
- English language: Correction of errors in english words and change gender job word to genderless job word.
- Action Builder: Added option to update or use json field from real model.
- STUDIO: add 'attrs' for User.
- Studio: Added colSpan,title for the label and  visibleInGrid option for button.
- Studio: Added restriction for model and model field names, allowed only alphanumberic characters.
- Studio: Disable 'Visible in grid' option for spacer.
- STOCK MOVE LINE: display invoiced status at same place as available tag.
- Company: Replace the M2M bankDetailsSet with O2M.
- BANKDETAILS: Add tree and card view for bank details and balance viewer on company bank details.
- BANK STATEMENT: update automatically balance and date of bank details concerned by the bank statement when imported.
- ACTIONBUILDER: Update filter on valueJson and metaJsonField fields.
- MetaJsonField: show sequence and appBuilder field in json-field-grid.
- ACTIONBUILDER: Allow to add a condition at start in generated action-script.
- SEQUENCE: enable tracking for most fields.
- BANK ORDER: Bank order workflow pass from draft to validated when automatic transmission is not activated in payment mode.
- INVOICE: add specific note of company bank details on invoice report.

## Bug Fixes
- Studio: Fix access to json fields of base model in chart builder form.
- Fix "could not extract ResultSet" Exception on finalizing a sale order.
- Studio: Fixed display blank when you click on a field which is out of a panel.
- Studio: Fixed selection filter issue and sequence issue.
- StockMoveLine: Fixed empty popup issue while viewing stock move line record in form view.
- STOCK MOVE LINE: fix $invoiced tag displayed twice.
- LEAVE TEMPLATE: changed field fromDate and toDate name to fromDateT and toDateT.
- MRP: Fix error while generating all proposals.
- UI: Addition of onClick attributes in buttons.
- Sales dashboard: Fix chart not displayed.
- PRODUCT: Fix economicManufOrderQty displayed twice.

[5.3.0]: https://github.com/axelor/axelor-open-suite/compare/v5.2.5...v5.3.0
