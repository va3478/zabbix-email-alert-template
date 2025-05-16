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
Go to `Administration > Media Types > your_meida_type (e.g. "Email (HTML)")`

<img width="874" alt="Screenshot 2025-05-16 at 14 12 53" src="https://github.com/user-attachments/assets/bb16f908-2d7f-46fc-ac06-16f858b2b977" />

Update the `Message Templates` "Problem" and "Problem Recovery"

<img width="486" alt="Screenshot 2025-05-16 at 14 19 07" src="https://github.com/user-attachments/assets/7ff016ec-6a6f-46db-9d3d-ed3476c550e9" />

Input code into the Message field.

<img width="692" alt="Screenshot 2025-05-16 at 14 19 30" src="https://github.com/user-attachments/assets/3583ad35-2873-485a-aeea-3eb7d7c76fb2" />

For more details on Zabbix Media Type configuration, please refer to: [MEDIA TYPES](https://www.zabbix.com/documentation/7.0/en/manual/config/notifications/media)


---
Inspired by: https://github.com/diasdmhub/Zabbix_Html_E-mail_Template
