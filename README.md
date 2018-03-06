# JsForm

A simple example for fill in the form automatically.



### Step 1 .F12 / Developer Console 

### Step 2.Copy the code blow and execute it.



`var delay=1000;`

`function buy(){doRedeemForm('629');$('[name=xingming]').val('bilibili');$('[name=phone]').val('23333');$('[name=address]').val('DoYouKnowIT');document.querySelector('.btn-success').click();setTimeout("cancle()",delay);} `

`function cancle(){document.querySelector('.btn-default').click();setTimeout("buy()",delay);} buy();`

##### Btw,it the element not have property "name" and have property "id" only,you can use `document.getElementById('')`