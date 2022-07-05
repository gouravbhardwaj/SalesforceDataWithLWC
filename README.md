# SalesforceDataWithLWC
Having a good knowledge of Lightning Web Component (LWC) can definitely give your CV a boost if you are a Salesforce Developer. But most importantly knowing the standard out-of-the-box features provided by the Salesforce platform is a must to become a good Salesforce Developer.

Today we are going to see the Top 3 ways in which you can work with Salesforce data from your Lightning Web Component (LWC).

What are we going to learn in this tutorial :

1. Using Base Lightning Components provided by the Salesforce platform that makes working with data super easy. (EASY: Minimal code required HTML/JS, No APEX)
2. Using wire services provided by the Lightning framework. (INTERMITTENT: Some amount of JS code required, No APEX)
3. Use Apex to get better control over your data and how you design the complete UI/UX in LWC. (ADVANCED: JS and APEX involved)
4. Using Base Lightning Components build on Lightning Data Services

There are three Standard Base Lightning Components built on Lightning Data Services which can be used to easily interact with Salesforce Data.

lightning-record-form: You can use lightning-record-form to quickly build a form to create, read or update a Salesforce record. Creating a form using this component is the easiest way of doing it as there are no customization required to build the form manually.
lightning-record-form is less customizable, in order to customize the layout as per your choice and conditionally render fields you can use lightning-record-view-form (to view data) and lightning-record-edit-form (to edit data).

lightning-record-form provides the below feature, which makes implementing it an ease.

a. Switch between view and edit modes with the click of the pen icon.

b. Save and Cancel button is rendered automatically when in the edit mode.

c. It utilizes the default field layout of the Object which supports multiple columns layout.

d. Load all the fields in the Object’s compact or full layout or specify the fields that you want to display.
