# Team MOHFW – Casual Wear Order Form

Simple web form to collect name, size and quantity for the black polo (Milandhoo Health Centre / TEAM MOHFW).

## Features

- Shows the polo photo and full size chart
- Collects: Full Name, Size (Adult + Kids), Quantity, optional notes
- **Every submission automatically downloads a CSV file** with all orders so far
- You can also manually download the submissions file at any time
- Orders stay in the browser (localStorage) until you clear them

## How to use the submissions file

1. People open the form and submit their size.
2. Each time someone submits, a file named `MOHFW_Casual_Wear_Orders_YYYY-MM-DD.csv` is downloaded.
3. Open the CSV in Excel / Google Sheets to see the full list (Name, Size, Quantity, Notes, Time).

## Deploy to Vercel (recommended)

1. Go to [vercel.com/new](https://vercel.com/new)
2. Import the GitHub repository `adamad2111/mohfw-casual-wear-order`
3. Click Deploy
4. After deploy, upload the two images (`polo.jpg` and `size-chart.jpg`) into the project (or replace the `<img>` tags with your own image URLs)

## Local use

Keep these three files in the same folder and open `index.html` in a browser:

- `index.html`
- `polo.jpg`
- `size-chart.jpg`

## Files needed for images

Please add the two image files to the root of this repository:

- `polo.jpg` – the black polo shirt photo
- `size-chart.jpg` – the size chart

You can drag & drop them on GitHub → Add file → Upload files.
