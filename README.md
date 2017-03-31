# toastJS
A light weight JAvascript library for showing customized toast messages in websites

Add toast.js to html and use the showError() method to display message .

##showError(param1,param2,param3);
param1 - message
param2 - type of message ('success','error','loading')
param3 - if true, hide the message after 2 seconds . 
         false, the message will not hide from screen unless hideError() method is called.

##hideError() 
Hides the toast message fom the screen.

###Error Toasts
showError('message','error',true);

###Loading Toasts
showError('message','loading',true);

###Success Toasts
showError('message','success',true);
