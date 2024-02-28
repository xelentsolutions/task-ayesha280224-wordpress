# WordPress Developer Coding Task: Custom Post Type Integration with WooCommerce


## Ayesha - 28-02-2024

### Objective:
Create a custom post type named "Brands" and make its data available as a dropdown selection in the WooCommerce product edit page. Selected brand information should then be displayed on the product's front-end page, right after the product title.

### Task Details

#### Create a Custom Post Type "Brands":
- Register a new custom post type called "Brands" with labels and supports title and thumbnail.
- Make sure the "Brands" post type is publicly queryable

#### Add a Brand Selection Dropdown to WooCommerce Product Edit Screen:
- Hook into WooCommerce product data metaboxes to add a new field under the General tab (or create a new tab if you prefer) where users can select a brand from a dropdown list.
- The dropdown options should be dynamically populated with all available entries from the "Brands" custom post type.

#### Store Selected Brand Information with the Product:
- Make sure the selected brand from the dropdown is saved when the product is updated.
- Use appropriate WooCommerce hooks for saving custom field data.

#### Display Selected Brand Information on the Product Front-end:
- Hook into the WooCommerce template system to display the selected brand's name and the logo right after the product title on the product detail page.
- Make sure this modification is done in a way that respects theme overrides, possibly by using WooCommerce hooks such as woocommerce_single_product_summary.

## Submission Requirements

- Provide the PHP code for the custom post type registration, the code to add and save the custom dropdown in the WooCommerce product meta box, and the code to display the brand information on the product front-end.
- Instructions on where to place the code (e.g., a custom plugin, theme's functions.php, or a child theme) and any additional setup required. It's up to you to approach for a solution.
