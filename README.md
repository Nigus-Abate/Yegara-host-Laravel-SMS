# Yegara-host-Laravel-SMS
This is how we implement Yegara host #SMS getaway using the popular framework #Laravel.  
Yegara HOST offers a Template-Based SMS API. you can use our API to send OTP, confirmation, reminders, and more.

Requests to our SMS API are sent to the following URL:

https://sms.yegara.com/api2/send  
Note that only 1 request can be processed at a time, so please wait for your current request to finish before sending another request.

The request should have the following parameters:  
|REQUEST PARAMETER  |    EXPLANATION|  
|$username and $password	| Your credential to access the API, which is available in your yegara.com account. see how you can generate it Here|  
|$to | | The user’s phone number you want to send the SMS to, you can use the following formats ‘+251960171717’, ‘251960171717’, ‘0960171717’ or ‘960171717’|  
|$message | | a list of comma-separated values to replace placeholders in the template  
|$template_id	| | $template_id|  


[Click here](https://example.com](https://my.yegara.com/index.php?fuse=knowledgebase&controller=articles&view=article&articleId=8)https://my.yegara.com/index.php?fuse=knowledgebase&controller=articles&view=article&articleId=8) to visit the website offical documentation.

