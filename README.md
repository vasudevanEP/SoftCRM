# B2B CRM System in Laravel 6.10 with PHP [>7.3]

SoftCRM is a database system containing a number of useful functions and solutions to facilitate B2B company management. It uses data analysis about customers' history with a company and to improve business relationships with customers, specifically focusing on customer retention and ultimately driving sales growth.

<img src="https://i.ibb.co/0ZfbYvC/Przechwytywanie.png">

## <font color="red">IMPORTANT!</font> 
In the future, administrators can define the default language to be applied to all site content. At the moment, SoftCRM supports English (you can configure your i18n). 
## Functionality:
<ul>
  <li>Contact Management</li>
  <li>Sales Team and Customer Opportunity Management</li>
  <li>Lead Management for determining high-quality leads</li>
  <li>Reports and Dashboards</li>
  <li>Sales Analytics</li>
  <li>Sales Force Automation</li>
  <li>Workflow and Approvals</li>
  <li>Sales Data</li>
</ul>

## Installation

#### 1. To install run the following commands in a working directory: 
```
git clone https://github.com/KamilGrzechulski/SoftCRM.git
```
#### 2. Now run and make sure you have composer installed on your server:
```
composer install 
```

#### 3. Then setup your database and open the .env.example file. Rename this file to .env and enter details for your site, database, stripe and email integration.

#### 4. Run this command from the root project folder and this will create the database tables for you. This is our custom command to process all missing features.
```
php artisan process-softcrm
```

#### 5. Than run laravel server by command:
```
php artisan serve
```

#### 6. Now you can login your Admin account by using:
```
user: admin@admin.com
password: admin
```


# Now you should then be able to access SoftCRM easily!

I see that you have come to the end. Do you appreciate my work on <strong>SoftCRM</strong>? Give me a virtual beer using Paypal !
<img src="https://i.ibb.co/NmFYNfx/beer-1.png">


[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=KVZEXQKGZU2ZN&currency_code=USD&source=url)
