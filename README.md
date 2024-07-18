# Personal-Finance-Management-App

Overview: As a university student, tracking down our finances and managing our money efficiently becomes extremely important. This app has various features to facilitate personal finance management. 

Features:
This app is divided into three broad categories: 
1. **Accounts:** This section keeps track of money present in different accounts you hold. It's broadly categories into 2 groups: Cash account and Bank account. It even allows you to create a new account. 
2. **Transaction History:** As the name suggests, it gives you the history of transactions you have made in a given period. It also displays the amount credited, debited, and net for a given period. By default, it shows the monthly transaction. There is an option for filter which allows you to view transactions for a given category, period, or account. 
3. **Reports:** Reports are again categorized into 2 parts: Income/Expense Statistics and Payable/Receivable reports.
Income/ Expense statistics show the pie chart of monthly transactions category-wise.
The payable/ Receivable report shows a table of the net amount to be paid/ received from different parties. This feature is useful for college students who regularly borrow money from their friends. 
Last but not least, this app also allows us to export our data as an Excel sheet.

**The technology used:** SQLite, Figma Software, Flutter
I have worked on designing the app's interface and database.
**Development:** 
Reason to choose Flutter:
I want this to be a cross-platform app and hence decided to go with Flutter because it allows you to write a single codebase for both iOS and Android, ensuring consistent performance and appearance. It offers a rich set of pre-designed widgets, fast development with hot-reload, and strong community support, making it efficient and cost-effective.

Reason to choose SQLite as a database engine: 
I want this application to be an offline-first application because the main aim of this app is that users should be able to access it at any time, even in the absence of the internet. This will be useful in scenarios where internet connectivity is an issue (eg: during travel or  living in a hostel, etc). Therefore, I decided to choose SQLite because it's lightweight, efficient, and supports offline functionality. Its easy integration with Flutter, robust security, and good performance for small to medium databases make it a reliable choice.

**Demo:** https://www.figma.com/proto/FDBoKS0SACCkATna3Na896/App-UI?node-id=19-241&t=EYJZN6hDwfIhifL7-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=86%3A514&show-proto-sidebar=1

Project Resources
1. UI Design: The UI design for the app is detailed in the AppDesign.pdf file.
2. Database: The database for this app is available in the pma.db file.

