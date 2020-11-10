# Spb Generator 

This integration provides the merchant with the ability to create a custom SPB button hosted on your server and can be shared as a link to your customers. The button will have the specific amount previously configured and a custom description in order to identify it easily. 


## Configuration 

1. Download this project. 

2. Open the payment.html file and chhange <INSERTE-CLIENT-ID> for your client ID on the line 11 th get your [PayPal API credentials](https://developer.paypal.com/docs/api/overview/#get-credentials)  
`<script src="https://www.paypal.com/sdk/js?currency=USD&client-id=<INSERTE-CLIENT-ID>"></script>`

3. Locate this folder with the CLIENT configuration and be aware of the location of the file payment.html file inside your server in a place it is available for your internal team and not externally. 

4. Once you have the folder on your server, open the index.html and change the line 27th INSERTE-DIRECTORIO-DE-PAGOS for the location of the  payment.html file  `  <input type="text" class="form-control" id="cfgitem-base" name="base" value="INSERTE-DIRECTORIO-DE-PAGOS">`  Save changes to the file. 

5. Upload and update this project into your server. 

6. Use the link of the location I.E. youurdomain.com/spbGenerator and let your team configure the buttons and share the links! 
