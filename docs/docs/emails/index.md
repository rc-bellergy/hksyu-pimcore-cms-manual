# Email Templates 

## Create an email

On panel tree, Select the place that you want the create an email template.  
Right click and select `Add Email` > `Formbuilder Email`

![](images/e01.png)

> To create/link a form, please [click here](forms/)

> For more information of Operation in Documents, please [click here](basic/interface)

## Edit an email

Open the email template, there is a ckeditor.  
Type any contents such as texts, images, parameters, HTML code, etc...

![](images/e02.png)

```
Note: Anything changed, please click the save button!
```

* **HTML code(For advanced user)**  
![](images/e02.1.png)
Among those email clients that do support HTML, some do not render it consistently with W3C specifications, and many HTML emails are not compliant either. Therefore, it leads to problems if the recipient's email client does not support it. In the worst case, the recipient will see the HTML code instead of the intended message.  
<br>To save HTML code, please click the `OK` button first then click the `Save` button on the toolbar.

* **Parameters**  
What are these parameters? , please [click here](#get-email-parameters)

## Preview email
The ways of preview:
- [Preview in the cms](#preview-in-the-cms)
- [Preview in the browser](#preview-in-the-browser)
- [Preview in the mail client](#preview-in-the-mail-client)

### Preview in the cms

Switch the `Edit` tab to `Preview`

![](images/e03.png)

### Preview in the browser

Click the preview icon on the toolbar to `Access via Public Mode`/ `Access via Preview Mode`
> About the toolbar, please [click here(toolbar)](basic/interface?id=toolbar)


### Preview in the mail client

Click the `Send Test-email` icon on the toolbar, then it shows the sent form. Fill up the [parameters](#get-email-parameters) if you need.

![](images/e04.png)

Then, click the `send` button and it shows the confirmation box. Select `Yes`

![](images/e05.png)

Received the mail in mail client

> To check the sent email record, please [click here](#check-sent-email-records)

## Get email parameters

Every email template may have their own parameters. Get the parameters from the form builder.

Here is an example:

Go to [formbuilder](forms/), select the form setting and open the field name.

`Name` is a parameter name.

![](images/e06.png)

So, you can use it in your paragraph.

```
%Text(contact_name);
```

Use it in ckeditor or HTML mode

![](images/e06.1.png)

## Check sent email records 

There are two places that store the record of the email sender.  
[Global email record](#global-email-record)(All email templates) and [Single email record](#single-email-record)(One of the email templates).

### Global email record

![](images/e07.1.png)

![](images/e07.2.png)

### Single email record

Open the email template, then select `Sent Emails` tab

![](images/e07.png)

## Operation in email record list

![](images/e07.3.png)

* **Filter and search**

![](images/e07.3.1.png) Search the email by the keywords.

* **Preview sent email**

![](images/e07.3.2.png) Preview the received email.

* **Check the parameters**

![](images/e07.3.3.png) Check the pararmeters of this email.

* **Resent**

![](images/e07.3.4.png) Send this email again.

* **Remove record**

![](images/e07.3.5.png) Click it and remove the sent record

> It can't restore when removed the record.