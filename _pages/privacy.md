---
layout: page
title: Privacy
include_in_header: true
---

<p style="text-align: right">
<strong>Last updated</strong><br>{{ site.privacy__last_updated }}
</p>

# Privacy Policy
Your privacy is very important to us. This Privacy Policy covers how we collect, use, disclose, transfer, and store your information. Please take a moment to familiarize yourself with our practices and contact us if you have any questions.

<hr/>

The collection of data and personal information through your use of the {{ site.app_name }} app and its related services (the "Service") is governed by this Privacy Policy. The Service is provided by {{ site.your_name }}, distributed under his name or {{ site.business_name }} (the "Developer"), located in Las Vegas, NV, United States of America.

<br>

## 1.0 Collection and Use of Personal Information
Personal information is data that can be used to uniquely identify or contact a specific individual.
You may be asked to provide your personal information anytime you are in contact with us (like when you fill out our contact form or sign up for a newsletter). You are not required to provide the information we requested, but if you choose not to do so, in many cases this means we will not be able to provide you with our products or services or respond to your inquiries.

### 1.1 What personal information we collect
Here are a few examples of the types of personal information that we collect:

- When you visit our website, connect to our services, contact us, use our software, or subscribe to a newsletter, we collect a variety of information, including your email address, device information, IP address, and a record of your communication.
- When using our software, we collect additional information such as anonymized usage statistics, crash reports, device system information, application version, user language, and whether you've subscribed or paid for our service.

{% for passage in site.privacy_1_1__info_we_collect %}

- {{ passage }}

{% endfor %}



### 1.2 How we use your personal information
We collect and process any personal data in accordance with the relevant data protection regulations. This means we may progress your personal information for the purposes described in this Privacy Policy with your consent, if it is necessary for the performance of a contract to which you are party or in order to take steps at your request prior to entering into a contract, if it is necessary for compliance with a legal obligation to which the Developer is subject, or when we have assessed it is necessary for the purposes of the legitimate interests pursued by the Developer or by a third party to whom it may be necessary to disclose information.

- The personal information we collect allows us to keep you up to date on our latest product announcements, software updates, and services. You may at any time opt out of receiving such communications by contacting us. In particular, we only send your our newsletter with your prior consent, and you can opt out of receiving the newsletter anytime by clocking the unsubscribe link we include in each newsletter, or by contacting us.
- We also use the personal information we collect to help us create, develop, deliver, protect, and improve our products, services, content, and customer communications.
- We may use your personal information to send important notices, such as communications about changes to our terms, conditions, and policies. As this information is important to your interaction with the Developer, you may not opt out of receiving these communications.
- We may also use personal information for internal purposes such as auditing, data analysis, and research to improve our products, services, and customer communications.

<br>

## 2.0 Collection and Use of Non-Personal Information
Non-personal information is data that cannot, on its own, be used to uniquely identify a specific individual. We may collect, use transfer, and disclose non-personal information for any purpose. We may combine personal and non-personal information for certain purposes; this data will then be treated as personal information for as long as it remains combined. Conversely, aggregated information, i.e. data that might have originated from personal information but that has been processed in such a way as to not allow personal identification, is treated as non-personal information.

<br>

## 3.0 Cookies and Other Technologies
Our website, services, apps, email communications and advertisements may use "cookies" and other technologies such as "pixel tags" and "click-through URLs".

We use the information we collect in this manner to better understand our users' interaction with our website and to optimize the user experience. You can disable cookies in your browser settings, but please note that certain features on our website may not be available as a result.

In our email communications, we may use other technologies like "pixel tags" and "click-through URLs" in order to determine if an email has been opened and which links have been clicked. We use this information to help us determine interest in particular topics and improve the effectiveness of our communications, and to reduce or eliminate messages sent to customers. Pixel tags are small images shown inside an HTML email; you can disable tracking by disabling HTML in your email client. A link with a click-through URL, when clicked, first sends the user to a web server which records the click, and then to the link's destination. If you prefer not to be tracked in this way, you should not click text or graphic links in the email messages.

As you access our services, we gather some information automatically on our servers and store it in log files. This information includes your browser type, version, and language, your operating system, the referring and exit websites, IP address, a date/time stamp of the request, and the requested resource (file name and URL). We use this information in anonymized form for statistical analysis, to administer our site, and to improve our product and services, without directly associating this data with individual users.

<br>

## 4.0 Disclosure to Third Parties
We don't share personal information with anyone outside the development team, except for the few exceptions below.

We work together with other companies ("Subcontractors") who provide information processing services. We only share personal information with these companies if you have agreed to the transfer, or if it is permitted by data protection lay. The information we share is limited to the data necessary for the third parties to provide their services. We use these companies for the following services: hosting of our website and data servers, cloud services, sending newsletters, facilitating customer communication, processing app usage and analytics, storing and analyzing crash reports. These companies are obligated to protect your information in accordance with data protection lay and provide the necessary safeguards. The companies are bound by our instructions, and are not allowed to use the shared data for any other purpose.

#### Subcontractors

{% for subcontractor in site.privacy_4_0__subcontractors %}
{% if subcontractor.name %}
- **{{ subcontractor.name }}** ({{ subcontractor.country }}) – *{{ subcontractor.description }}*
{% endif %}
{% endfor %}

We also share personal information if disclosure of such information is reasonably necessary to satisfy any applicable law, regulation, legal process or enforcable govermental request; to enforce applicable Terms of Service, including investigation of potential violations thereof; to detect, prevent, or otherwise address fraud or security issues; and to protect against harm to the rights, property or safety of the Developer, its users or the public as required or permitted by law.

If the Developer is involved in a reorganization, merger, or sale, the information we collect may be transferred as part of that transaction.

<br>

## 5.0 Protection of Personal Information
We take appropriate security measures to protect against unauthorized access to or unauthorized alteration, disclosure or destruction of data. These include internal reviews of our data collection, storage and processing practices and security measures, including appropriate encryption and physical security measures to guard against unauthorized access to systems where we store personal data.

Inside our small development team, we restrict access to personal information to only those who need to know that information in order to deploy and maintain our services. These individuals are typically bound by confidentiality agreements and may be subject to discipline, including termination and criminal prosecution, if they fail to meet these obligations.

Whenever your connect to our website we use encryption such as Transport Layer Security (TLS) for all information that is being transmitted. In-app activity and data is transmitted using the framework provided by Apple. However, no method of transmitting or storing data is 100% secure, so we cannot guarantee the security of information your transmit to us.

<br>

## 6.0 Access to Personal Information
You are entitled to request information about the personal data stored by us, to have incorrect data corrected, or to request the freezing or deletion of your data. We will, within a reasonable timeframe, remove all data associated to your that is stored on our servers and storage configurations. We will also request the deletion of any personally identifiable information from the storage of our subcontractors wherever possible.

Your personal information is retained for as long as it is necessary in order to fulfill the purposed outlined in this Privacy Policy, to enforce applicable Terms of Service, or to comply with our legal obligations.

<br>

## 7.0 Children
We do not knowingly collect personal information from children under 16, or equivalent minimum age in the relevant jurisdiction, unless their parent provided verifiable consent. If we learn that we have collected personal information from a child under 16, or equivalent minimum age in the relevant jurisdiction, without consent of their parent, we will take steps to delete this information as soon as possible. Parents or guardians can contact us.

<br>

## 8.0 Third-Party Sites and Services
Our website or any of our services may contain links to third-party websites or services. We are not responsible for the information collected by those third parties and we encourage you to read their privacy policy before submitting any personal information to them.

<hr/>

Our Privacy Policy may change from time to time. When we change the policy, we will post the changes on this page. If the policy changes in a significant way, we will also provide notice on our website, and attempt to notify in other areas our service is available.
