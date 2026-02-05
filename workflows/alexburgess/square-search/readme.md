# Square Search

This  workflow allows you to search for items, customers, and dashboard pages in Square directly from Alfred. Simply type in one of the keywords followed by your search, and the workflow will fetch relevant results, providing quick access to product details, customer records, or key Square Dashboard sections—helping you navigate Square more efficiently.

### Item Search

![](images/item.png)

- Type in the item search keyword, followed by the item name
- It will display the item, along with its variation names + prices, and SKU number
- Press return to go to the item in the square dashboard

#### Get images of square products in Alfred
This workflow, will download a small copy of the product image, after you select an item to open in the dashboard. However, to download current images, you will want to type in the `initsquareimages` command

### Customer Search

![](images/customer.png)

- Type in the keyword, followed by an *email address, phone number, or reference number* of a customer in your directory
- It will display a list of matching customers, along with their details
- Press return to go to the customer in the customer directory

### Dashboard Search

![](images/dashboard.png)

- Type in the keyword, followed by the name of the square dashboard page you are looking for
- Press return to jump to that page


#### How to Get Your Square Access Token

To use this workflow, you’ll need a Square access token. Follow these steps to obtain one:
- Go to Square Developer Console [developer.squareup.com](https://developer.squareup.com/)
- Click *Create an Application* and give it a name
- Select your app from the dashboard, by pressing the 'open' button
- In the app settings, navigate to Credentials
- Locate the Personal Access Token under Production
- Copy the token, and paste it into the box in the configuration

**⚠️ Keep your access token secure—never share it or expose it in public repositories**

---

##### Disclaimer

This workflow is independently developed and is not created, endorsed, or maintained by Square. Square’s name and logos are trademarks of Block, Inc. and are used here solely for identification purposes. Use this workflow at your own discretion