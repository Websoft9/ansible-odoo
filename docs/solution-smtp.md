# SMTP

Sending mail is a common feature for Odoo. After a large number of user practice feedback, only one way is recommended, that is, using the **third-party STMP service** to send the email.

> Do not try to install **Sendmail** or other Mail server software on your Cloud Server for sending mail, because it is very difficulty in maintenance.

Follow is the sample using **SendGrid's SMTP Service** to configure sending mail for Odoo:

1. Log in SendGrid console, prepare your SMTP settings like the follow sample
   ```
   SMTP host: smtp.sendgrid.net
   SMTP port: 25 or 587 for unencrypted/TLS email, 465 for SSL-encrypted email
   SMTP Authentication: must be checked
   SMTP Encryption: must SSL
   SMTP username: websoft9smpt
   SMTP password: #fdfwwBJ8f    
   ```
2. Log in to the Odoo Console, intall the **Discuss** module that SMTP need
   ![Odoo SMTP](https://libs.websoft9.com/Websoft9/DocsPicture/en/odoo/odoo-discussmodule-websoft9.png)

3. Open **Settings** > **General Settings** > **Discuss** to start configure SMTP
   ![Odoo SMTP](https://libs.websoft9.com/Websoft9/DocsPicture/en/odoo/odoo-gsetmail-websoft9.png)

3. Fill in the SMTP parameters
   ![Odoo SMTP](https://libs.websoft9.com/Websoft9/DocsPicture/en/odoo/odoo-smtps-websoft9.png)

4. Click the **Test Connection**

More SMTP Service(Gmail, Hotmail, QQ mail, Yahoo mail, SendGrid and so on)  settings or Issues with SMTP, please refer to Websoft9's *[SMTP Guide](https://support.websoft9.com/docs/faq/tech-smtp.html)*