---
copyright:
  years: 2014, 2018
lastupdated: "2018-02-22"
---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

<a name="top"></a>
# FAQs: SSL certificates

## Why doesn't the SSL certificate that I ordered automatically show up on the SSL certificates screen?

SSL certificates are issued by a third-party certificate authority, which sends all of the certificate details directly to you in a confidential email. After receiving that email, you have the option to [import the SSL certificate](import-ssl-certificate.html) to the {{site.data.keyword.slportal_full}} should you choose to use the certificate with {{site.data.keyword.BluSoftlayer_full}} products and services. Because {{site.data.keyword.cloud_notm}} never receives the details for SSL certificate, data cannot be imported automatically.

## What is an SSL certificate?

SSL certificates are enabled by websites as a security measure to protect the user. They are generally used when you are required to transmit confidential information to a website, such as name, address, credit card numbers, and other personal data or are managing data that requires authentication (such as in the {{site.data.keyword.slportal}}). SSL certificates are requested by the company that runs the website but are issued by a trusted, third-party company that ensures the validity of the website. Secure websites are preceded by HTTPS in the URL, as opposed to the standard HTTP.

## How can I order an SHA2 SSL?

If you already ordered an SSL and it is showing errors that the SSL certificate is using SHA-1 instead of SHA-2, you need to request that the SSL is re-issued. You can do this by submitting a ticket.

If you have not yet ordered an SSL from {{site.data.keyword.cloud_notm}} and need to order one with SHA-2, submit a ticket to manually order an SSL for the domain in question. {{site.data.keyword.slportal}} still automatically creates SSL certificates using SHA-1, so if you do this, you will then need to have it re-issued.
