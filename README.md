# Thyme & Whisk — Premium QR Ordering Website

Restaurant: Thyme & Whisk, Shop No. 13/14 Bosco Centre, Prasad Circle, Gangapur Road, Nashik, Maharashtra 422005.
Phone: +91 97260 00068
Maps: https://maps.app.goo.gl/qJ21Z1Gfq9GfTs6C6

## Included
- Responsive premium animated customer menu and cart
- Supabase-backed order creation and order tracking
- Table QR URL support: `?restaurant=RESTAURANT_UUID&table=TABLE_UUID`
- Staff login, waiter and kitchen workflows
- Photo assets in `images/`
- GitHub Pages deploy workflow

## Setup notes
This app retains the existing Supabase configuration and schema from the earlier QR system. The restaurant and table IDs must exist in that database; update the default IDs in `index.html` to the actual restaurant/table UUIDs if needed. Add menu rows and ensure their names/categories are accurate.

Staff dashboard: `?staff=1`

## Deployment
GitHub Actions deploys the static site. In repository Settings → Pages, select **GitHub Actions** as the source if not already selected. Check the Actions tab for deployment status.
