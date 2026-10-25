# SmartShelf

SmartShelf is a simple web app for small shops in Kigali. It helps a shop owner sell, track stock and prices, record debts, and see daily profit, all from a phone.

## What it does

- **Sell:** tap a product, choose the quantity and price, and mark the sale as Paid or On credit. Stock goes down automatically.
- **Stock:** add a new product at any time with its buying price, selling price and quantity. The app shows the profit per item. You can edit prices, add more stock, or delete a product.
- **Debts:** credit sales are added to the customer's debt automatically. You can add old debts, record payments, and send a WhatsApp reminder with one tap.
- **Report:** pick any date to see sales, cost of goods sold, profit, stock bought, credit given, and debts collected, with the profit for each product.
- **Languages:** Kinyarwanda and English, with a switch at the top.

## How it works

SmartShelf is a single `index.html` file. It has no server and no database. The data is saved in the browser on the phone (localStorage), so each phone keeps its own records. Clearing the browser data erases them.

## Deploy on Render

1. Upload `index.html`, `render.yaml` and `README.md` to a GitHub repository.
2. On [render.com](https://render.com), choose **New**, then **Static Site**, and connect the repository.
3. Leave the build command empty and set the publish directory to `.`
4. Click **Create Static Site** and open the link on a phone.

## Add to the phone's home screen

- **Android (Chrome):** menu, then **Add to Home screen**.
- **iPhone (Safari):** Share, then **Add to Home Screen**.

## Limits of this version

- Data is stored on one phone only and is not backed up.
- There are no user accounts or passwords.
- The Kinyarwanda wording should be checked by a native speaker before wider use.

## Roadmap

- Backend with a database and login, so data is safe and works on any phone
- WhatsApp agent version
- Data export to Excel

## Author

Tuyizere Christian, AI Technology student, United African Institute of Technology (UAIT), Kigali, Rwanda.# Smartshelf-
