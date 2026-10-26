# Inventory Dashboard: Starter Folder

The starting point for the **Responsive Web Design with AI Assistance** class.
You will build one inventory dashboard several ways: plain HTML and CSS, then Bootstrap, then Tailwind CSS.

## Folder contents

| Path | What it is |
| --- | --- |
| `index.html` | Your dashboard page. Starts as a bare skeleton with a checklist of what to build. |
| `css/style.css` | Your stylesheet. Starts as an empty outline, filled in from Session 2. |
| `images/logo.svg` | A logo you can use in the top bar. Give it useful alt text. |
| `products.txt` | 15 sample products (SKU, name, category, quantity, price in KES). Use them for the inventory table. |
| `div-soup.html` | A messy page for the Session 1 refactoring exercise. Do not style it. |
| `.vscode/extensions.json` | Recommends Live Server, GitHub Copilot and Tailwind IntelliSense. |

## How to run it

1. Open the `inventory-dashboard` folder in VS Code (File, Open Folder).
2. Install the recommended extensions when VS Code asks.
3. Right-click `index.html` and choose **Open with Live Server**.
4. Edit and save. The page reloads on its own.

Open DevTools with **F12**, device mode with **Ctrl+Shift+M**, and the element picker with **Ctrl+Shift+C**.

## The dashboard you are building

| Area | Contents |
| --- | --- |
| Top bar | Logo, search box, user menu |
| Sidebar | Dashboard, Products, Orders, Suppliers, Reports, Settings |
| Summary cards | Total products, low-stock items, orders today, inventory value |
| Inventory table | SKU, name, category, quantity, status, price, actions |
| Add product form | Name, SKU, category, quantity, price, notes |
| Stock panel | Simple bar summary built with HTML and CSS |

Treat a product as **low stock** when its quantity is below 20.

## Versions you will build

| Session | Version |
| --- | --- |
| 1 | V1: semantic HTML skeleton |
| 2 | V1: styled with external CSS |
| 3 and 4 | V2: Flexbox and Grid layout, fully responsive |
| 5 | V3: Bootstrap dashboard |
| 6 | V4: Tailwind dashboard |
| 7 | Icons and audit |
| 8 | Final submission |

Keep each version in its own folder or Git branch (for example `v2-responsive`, `v3-bootstrap`) so you can compare them later.

## Working with AI

Predict, prompt, verify, review, explain, declare. Keep a note of the prompts you used and what you changed, because you will write an AI use statement in your README at the end.
