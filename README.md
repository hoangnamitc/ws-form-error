# wsFormError
This is plugin check error for form. FORM request with ajax.

#### USING:
````
$('#myDiv').wsFormError();
````

#### CUSTOM:
```
$("#myDiv").wsFormError({
    notification: true,
    callback: function(data) {
        if (data == 0) {
            // your task
        }
    }
});
```
#### TUTORIAL:
To using this plugin, you add class "ws-required" in input,textarea.....
- Check Number: you add class to input,textarea "ws-required-number"
- Check Phone: you add class to input,textarea "ws-required-phone"
- Check Email: you add class to input,textarea "ws-required-email"

#### NOTIFICATION:
To set content notification error of plugin you add html tags:
- data-wserror-xx="content message notification error" (xx: phone, email, number)

##### example:
```
<input type="text" name="phone" class="ws-required ws-required-phone" data-wserror-phone="Please enter number phone" />
```
