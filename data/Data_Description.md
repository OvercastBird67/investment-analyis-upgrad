### 1. Company details

__companies__: A table with basic data of companies

Description of Companies Table:

<table>
  <tr>
    <th>Attribute</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>Permalink</td>
    <td>Unique ID of company</td>
  </tr>
  <tr>
    <td>name</td>
    <td>Company name</td>
  </tr>
  <tr>
    <td>homepage_url</td>
    <td>Website URL</td>
  </tr>
  <tr>
    <td>category_list</td>
    <td>Category/categories to which a company belongs</td>
  </tr>
  <tr>
    <td>status</td>
    <td>Operational status</td>
  </tr>
  <tr>
    <td>country_code</td>
    <td>Country Code</td>
  </tr>
  <tr>
    <td>state_code</td>
    <td>State</td>
  </tr>
</table>

### 2. Funding round details

__rounds2__: The most important parameters are explained below

Description of rounds2 Table

<table>
  <tr>
    <th>Attributes</th>
    <th>Description
  </tr>
  <tr>
    <td>company_permalink</td>
    <td>Unique ID of company</td>
  </tr>
  <tr>
    <td>funding_round_permalink</td>
    <td>Unique ID of funding round</td>
  </tr>
  <tr>
    <td>funding_round_type</td>
    <td>Type of funding - venture, angel, private equity, etc.</td>
  </tr>
  <tr>
    <td>funding_round_code</td>
    <td>Round of venture funding (round A, B, etc.)</td>
  </tr>
  <tr>
    <td>funded_at</td>
    <td>Date of funding</td>
  </tr>
  <tr>
    <td>raised_amount_usd</td>
    <td>Money raised in funding (USD)</td>
  </tr>
</table>

### 3. Sector Classification:

__mapping.csv__: This file maps the numerous __category names__ in the companies table (such as 3D printing, aerospace, agriculture, etc.) to eight broad __sector names__. The purpose is to simplify the analysis into eight sector buckets, rather than trying to analyse hundreds of them.
