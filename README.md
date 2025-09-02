# Front Seller License Agreement (FSLA)

The **Front Seller License Agreement (FSLA)** is a protest license designed to empower the consumer by "flipping the script" on traditional, restrictive End User License Agreements (EULAs).

The core idea of the FSLA is to assert the buyer's rights to a purchased product or service at the point of sale, making these rights the priority over any other license.

### Purpose

In an age where EULAs often take away a consumer's ownership rights, the FSLA stands as a declaration of a different philosophy. By accepting a transaction with a user who agrees to this license, a seller automatically grants the user the following fundamental rights:

* **Copy:** The right to create and keep copies of the purchased product.

* **Distribute:** The right to share the purchased product with others.

* **Modify:** The right to alter or adapt the product as they see fit.

* **Sell:** The right to sell or transfer their copy of the product to another party.

The FSLA states that these rights take precedence over any other license agreement that might attempt to limit them. It is an intentional challenge to the idea that a customer buys a product but not the right to truly own it.

### How to Use

Just buy an item, then refer the seller to this project or website via email. Buy selling you a product they already agree to the terms of this FSLA and revoke their own EULA or other forms of control over the product they have sold you without needing to directly read it just like EULA would.

## Config for NGINX to use as a website:
```
server {
        listen 8080;
        listen [::1]:8080;
        server_name fsla.example.com;
        root /srv/fsla; # Upload index.html to this folder
        location / {
                access_log  /var/log/nginx/fsla.access.log;
                index index.html;
        }
}
```

## Example
For a public hosted version visit https://fsla.jester-designs.com/
