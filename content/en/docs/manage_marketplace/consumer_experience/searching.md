---
title: Search and filter Marketplace content
linkTitle: Search and filter Marketplace content
weight: 5
---

Learn how to search through content in the Marketplace.

## Search by keyword

Each main page has a search bar that allows you to type a keyword and refine the results.

**Products search** allows you to look for terms in:

* Product title
* Product description
* Markdown documentation
* Product categories
* API specification

From the **Category** page, you can search categories by:

* Title
* Description

From the **Applications** page, you can search applications by:

* Title

From the **Subscriptions** page, you can search subscriptions by:

* Product title
* Product description

The search looks for a partial or complete match with the keyword that is entered in the search bar. The search is refined as characters are entered. The number of found results is displayed in the search bar.

Click **x** on the search bar to reset the search.

## Filter a result

In addition to the search bar, filters that refine results are available on the left of the main pages (Products / Applications / Subscriptions), as well as on some detail pages (Product resources / Category details). Each filter is a collapsible panel.

Filter input controls:

* Radio button: single filter criteria
* Checkbox: multiple filter criteria
* Checkbox and search: multiple filter criteria and search capability to find the correct filter name

{{< alert title="Note" color="primary" >}}
When the screen is too small to display the filter and the page content at the same time, the filter displays as an icon on the left of the search bar.
Click the icon to expand the filter over the page content. Click it again to hide the filter.
{{< /alert >}}

The filter allows search values to reduce the number of items. Once selected, the page content is displayed according to the filter restriction.

### Home page search

Search is available when the home page is activated from the Marketplace settings.

* Search bar from Hero Content (if activated): search with any words matching a product title / description / specification content / Documentation (markdown only) / category title assigned to a product.
* Browse product: filter the recently published list of products based on product title / description / title assigned to a product.
  
### Product search

Use the search bar to find products by keywords with a match in:

* Product title
* Description
* API Specification
* Documentation (markdown only)
* Categories

#### Advanced search

When viewing the product list, refine your search with Advanced Search.

1. Click **Advanced Search** to replace the search bar with the Advanced Search component.

    * Enter multiple words and then select the appropriate matching parameter via a dropdown: **EQUALS**, **NOT EQUALS**.
    * When entering multiple words, you can decide the operator between those words: **OR** or **AND**. The drop-down on the matching parameter and on the operator allows you to adjust your criteria.
    * Click the **-** to remove the criteria. Click **Clear all** To reset the component.

2. Once you are satisfied with your criteria, click **Search**. The corresponding matching products are displayed.

Click **Reset** to remove the selected criteria and refresh the product list to the one that is visible by the user.

Click **Basic Search** to return to the Basic Search bar at any time.

#### Refine your findings with filters

Two filters are available:

* Category filter: view products that match one or more categories. If a category contains children categories, expand the category to view the children.
* Stages filter: view products that have specific resources and match a specific stage. The visible stages have been deployed to the Marketplace and the user belongs to teams that have visibility.

#### Product resources filter

When the provider assigns multiple assets to a single product, the resources can be grouped per asset when publishing the product to a Marketplace. The product resources search bar is then enriched with the filter component, enabling the consumer to filter the Resource Group.

### Categories search

* When viewing the categories list, use the category title or description in the search bar to refine the category findings.
* When browsing a specific category, use the product title or description in the search bar to refine the associated product findings.

#### Refine your findings with children category filters

Use the filters located at the left of the category detail page to filter the children categories of the currently displayed category.

* **Show sub-category products**: (selected by default) view all products linked to a children category of the current category. When not selected, all products associated to a children category are removed from the result list and only the products associated to the displayed category are listed.
* search bar: refine the children category list. When the filter matches several categories, the filter is highlighted in bold on the category names.

If a children category has children, expand the category to view of the children.

Once categories are selected, products matching the selected categories are displayed.

### Applications search

Find an application by entering the application title in the search bar.

#### Refine your findings with application state filter

Use the filter located at the left of the application page to filter by application state. Once a state is selected, applications matching the selected state are displayed.

### Subscriptions search

Find a subscription by entering the product title and/or description.

#### Refine your findings with category filter

Use the filter located at the left of the subscription page to filter by category. If a category contains children, expand the category to view the children.

### Consumer Insights filters

Use the drop-down filters located at the top of each Consumer insights page.

Filter functionality:

* **All kind** (default) select all
* 10 first items loaded + infinite loading (i.e., it loads 10 more items when reaching the end of the list)
* Refine the list capability

Filter definition:

* Product: show all products my team(s) has access to
* Subscriptions: show all subscriptions assigned to a product my team(s) has access to
* Applications: show all applications that have a subscription assigned to a product my team(s) has access to
* Methods: list the known methods (GET, POST etc.)
* Status code: All successes , All failures, All exceptions, All specific http codes

See [Consumer insights](/docs/get_actionable_insights/consumer_insights) for more information.