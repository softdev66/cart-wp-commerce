# WP eCommerce - Mercado Pago Module (3.11.x or greater)

* [Features](#features)
* [Available versions](#available_versions)
* [Requirements](#requirements)
* [Installation](#installation)
* [Basic Checkout Configuration](#std_configuration)
* [Upgrade](#upgrade)
* [Feedback](#feedback)

<a name="features"></a>
##Features##

Checkout option right for your business:
We offer a checkout method that make it easy to securely accept payments from anyone, anywhere.

**Basic Checkout**

Great for merchants who want to get going quickly and easily.

* Easy website integration — no coding required.
* Limited control of buying experience— display Checkout window as redirect, modal or iframe.
* Store buyer’s card for fast checkout.
* Accept tickets, bank transfer and account money in addition to cards.
* Accept Mercado Pago's discount coupons.

*Available for Argentina, Brazil, Chile, Colombia, Mexico, Peru and Venezuela*

<a name="requirements"></a>
##Requirements##

Basically, the requirements of this plugin are same as you need to run WP eCommerce. Your machine should have:

**Platforms**

* <a href="https://wordpress.org/download/">WordPress</a> 4.1 or greater;
* <a href="https://wordpress.org/plugins/wp-e-commerce/">WP eCommerce</a> 3.11 or greater;

**Web Server Host**

* <a href="http://php.net/">PHP</a> 5.6 or greater with CURL support;
* <a href="http://www.mysql.com/">MySQL</a> version 5.6 or greater OR <a href="https://mariadb.org/">MariaDB</a> version 10.0 or greater;
* <a href="https://httpd.apache.org/">Apache 2.x</a>.

<a name="available_versions"></a>
##Available versions##

<table>
  <thead>
    <tr>
      <th>Plugin Version</th>
      <th>Status</th>
      <th>WP eCommerce Compatible Versions</th>
    </tr>
  <thead>
  <tbody>
    <tr>
      <td>v4.0.0</td>
      <td>Stable (Current version)</td>
      <td>WP eCommerce 3.11.x or greater</td>
    </tr>
  </tbody>
</table>

<a name="installation"></a>
##Installation##

If you have already the module installed, please follow the [Upgrade instructions](#upgrade) first.

**Step-to-Step**

1. Get the module sources from a repository (<a href="https://github.com/mercadopago/cart-wp-commerce/archive/master.zip">Github</a>;

2. Unzip the folder and find "wpecomm-mercado-pago-module" directory;

3. Copy all files from "wpecomm-mercado-pago-module" directory to *[WordPressRootDirectory]/wp-content/plugins/wp-e-commerce/wpsc-merchants/* directory.

To confirm that your module is really installed, you can click in *Settings > Store > Payments* item in the store administration menu, and check your just installed module. Just *enable* the checkbox to activate it.

![Features](https://raw.github.com/mercadopago/cart-wp-commerce/master/README.img/plugin_adm.png)

<a name="std_configuration"></a>
##Basic Checkout Configuration##

On your store administration, go to *Settings > Store > Payments* tab. Click in *Mercado Pago Basic Checkout*. You should get the following page:

![Installation Instructions](https://raw.github.com/mercadopago/cart-wp-commerce/master/README.img/basic_checkout.png)

1. **Solution Header**: This part is the header, where you can enable/disable the solution and set the gateway name;

2. **Mercado Pago Credentials**: In this part, you should configure your credentials *Client_id* and *Client_secret*;

  Remember that you can obtain your *Client_id* and *Client_secret*, accordingly to your country, in the following links:

  * Argentina: https://www.mercadopago.com/mla/account/credentials?type=basic
  * Brazil: https://www.mercadopago.com/mlb/account/credentials?type=basic
  * Chile: https://www.mercadopago.com/mlc/account/credentials?type=basic
  * Colombia: https://www.mercadopago.com/mco/account/credentials?type=basic
  * Mexico: https://www.mercadopago.com/mlm/account/credentials?type=basic
  * Peru: https://www.mercadopago.com/mpe/account/credentials?type=basic
  * Venezuela: https://www.mercadopago.com/mlv/account/credentials?type=basic

3. **Checkout Options**: This part allows you to customize your general checkout fields;

  *Description*: This is the description of the payment option that will be shown to your customers;<br />
  *Store Category*: Sets up the category of the store;<br />
  *Store Identificator*: A prefix to identify your store, when you have multiple stores for only one Mercado Pago account;<br />
  *Integration Method*: How your customers will interact with Mercado Pago to pay their orders;<br />
  *iFrame Width*: The width, in pixels, of the iFrame (used only with iFrame Integration Method);<br />
  *iFrame Height*: The height, in pixels, of the iFrame (used only with iFrame Integration Method);<br />
  *Auto Return*: If set, the platform will return to your store when the payment is approved;<br />
  *URL Approved Payment*: This is the URL where the customer is redirected if his payment is approved;<br />
  *URL Pending Payment*: This is the URL where the customer is redirected if his payment is in process.

4. **Payment Options**: This part allows you to customize how the payment should be made;

  *Max Installments*: The maximum installments allowed for your customers;<br />
  *Currency Conversion*: Let merchants try to convert unsupported currency into Mercado Pago supported currency;<br />
  *Exclude Payment Methods*: Select the payment methods that you want to not work with Mercado Pago.

5. **Test and Debug Options**: This part allows you to configure debug and test features.

  *Mercado Pago Sandbox*: Test your payments in Mercado Pago sandbox environment;<br />
  *Debug and Log*: Enables/disables system logs.

<a name="upgrade"></a>
##Upgrade Mercado Pago Plugin##

If you already had installed a previous version of WPeComm Mercado Pago Module, please follow the instructions. The process of update is very similar to installation.

**Step-to-Step**

1. Get the module sources from a repository (<a href="https://github.com/mercadopago/cart-wp-commerce/archive/master.zip">Github</a>;

2. Unzip the folder and find "wpecomm-mercado-pago-module" directory;

3. Go to *[WordPressRootDirectory]/wp-content/plugins/wp-e-commerce/wpsc-merchants/* directory and delete the existing files "mercadopago-basic.php", "mercadopago-images", "mercadopago-languages", and "mercadopago-lib";

4. Copy all files from "wpecomm-mercado-pago-module" directory to *[WordPressRootDirectory]/wp-content/plugins/wp-e-commerce/wpsc-merchants/* directory.

To confirm that your module is really updated, you can click in *Settings > Store > Payments* item in the store administration menu, and check your just updated module. The version should match the just-updated plugin.

<a name="Feedback"></a>
##Feedback##

We want to know your opinion, please answer the following form.

* [Portuguese](http://goo.gl/forms/2n5jWHaQbfEtdy0E2)
* [Spanish](http://goo.gl/forms/A9bm8WuqTIZ89MI22)
