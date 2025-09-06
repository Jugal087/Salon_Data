Salon Data Manager
This is a web-based dashboard for managing and analyzing salon data, including customer information, VIP memberships, staff performance, and financial reports. The application is designed to be hosted online and syncs data directly from a public Google Sheet.

Features
Live Data Sync: Fetches and displays data from a Google Sheet in real-time.

Staff Dashboard: Track individual staff performance, calculate salaries with incentives, and view their service history.

Customer Profiles: A complete directory of all customers, with detailed profiles including visit history, total spending, and favorite staff members.

VIP Management: Separate views for active and expired VIP members, with key metrics for retention.

In-depth Reports:

Monthly Summary: A comprehensive overview of revenue, services, and customer acquisition.

Frequent Customers: Identify and analyze your most loyal clients.

Expected & At-Risk Customers: Proactively manage customer churn by identifying clients who are due for a visit or have become inactive.

Fully Responsive: The layout is optimized for viewing on desktops, tablets, and mobile devices.

How to Use
1. Prepare Your Google Sheet
Create a new Google Sheet.

Set up your sheet with the following case-sensitive column headers in the first row:

Date (format: DD-MM-YYYY)

Phone

Name

Services

Staff

Member

Total

Paid

Type (This is crucial. Use 'Service' for a regular customer entry, 'VIP' for a new VIP signup, and 'Staff' to list a staff member's name.)

Example Rows:
| Date | Phone | Name | Services | Staff | Member | Total | Paid | Type |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 01-08-2025| 9876543210| Jane Doe | Haircut, Manicure | Alice | Normal | 1500 | 1500 | Service |
| 02-08-2025| 1234567890| John Smith| - | Bob | VIP | 5000 | 5000 | VIP |
| 03-08-2025| - | Alice | - | - | - | - | - | Staff |
| 03-08-2025| - | Bob | - | - | - | - | - | Staff |

Publish your sheet:

Go to File > Share > Publish to web.

In the dialog box, make sure Entire Document and Web page are selected.

Click Publish.

Important: Go back to File > Share > Share with others.

Under General access, change it to Anyone with the link.

Click Copy link and then Done. This is the link you will use in the app.

2. Deploy to GitHub Pages
Create a GitHub Account: If you don't have one, sign up at github.com.

Create a New Repository:

Click the + icon in the top right and select New repository.

Give it a name (e.g., salon-dashboard).

Make sure it's Public.

Click Create repository.

Upload the Files:

In your new repository, click on Add file > Upload files.

Drag and drop the Shop_Data.html and README.md files into the browser window.

Click Commit changes.

Enable GitHub Pages:

In your repository, go to the Settings tab.

On the left menu, click on Pages.

Under Branch, select main (or master) and keep the folder as / (root).

Click Save.

It might take a minute or two, but your site will be live at a URL like https://your-username.github.io/salon-dashboard/Shop_Data.html. GitHub will display the exact URL on this page.

3. Sync Your Data
Open your newly deployed website.

Paste the public Google Sheet link (from step 1.3) into the input field at the top.

Click the "Sync Data" button.

The application will fetch all the data from your sheet and populate all the tabs and reports.

Enjoy your new live Salon Data Manager!