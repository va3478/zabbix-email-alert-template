# zabbix-email-alert-templates

### Customized Zabbix HTML Email Alert Problem and Problem Recovery Templates

The repository contains a set of cutomized HTML templates to be used with the Zabbix Email HTML MediaType. 

## Requirements

- Zabbix 6.5 and up
- Zabbix Media Type cofigured with the HTML or Markdown message format

## Customization
---
It can be customized many tags depend on your HTML skills.

I used this resource for coding: [w3school](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_default_default)

[HTML Templates](./Template/html/)

### Sample. HTML Templates Problem & Problem Recovery
---
<img width="427" alt="Screenshot 2025-05-16 at 12 49 07" src="https://github.com/user-attachments/assets/9878eb45-6f06-4d0b-bb7a-702193fca2a4" />
<img width="435" alt="Screenshot 2025-05-16 at 12 47 34" src="https://github.com/user-attachments/assets/945dcd5a-7f97-4a6c-ba88-c6b3dc4d728c" />

## Installation

---
Go to `Administration > Media Types > Email (HTML)`


Update the `Message Templates` "Problem" and "Problem Recovery"



For more details on Zabbix Media Type configuration, please refer to: [MEDIA TYPES](https://www.zabbix.com/documentation/4.4/manual/config/notifications/media)

### ToDo

---
- Add link to Event Details
- Add a Graph to the problematic item

---
Inspired by: https://github.com/diasdmhub/Zabbix_Html_E-mail_Template
