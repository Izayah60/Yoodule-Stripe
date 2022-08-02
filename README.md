# Instructons

1. Create a WordPress plugin called Yoodule Stripe.

2. Once installed, a WordPress admin menu called Yoodule Stripe would be inserted, when clicked redirects to a plugin page where the Stripe api credentials can be specified and saved to the database as a WordPress option.

3. Create a shortcode named [yoodule_stripe], this shortcode once inserted on any page should render a table using jQuery Datatables. The table in question will get data using jQuery.Datatables({ajax:...}), which would make an Ajax request fetching all the prices from Stripe and all pagination requests would be passed via Ajax to backend and rendered accordingly.

4. The plugin source code should be hosted on a public git repository and once installed, it should be easy to switch to a different stripe account by changing the api credentials in step 2.
