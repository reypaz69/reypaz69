# how to use arclem omada voucher checker

1. register an account on rapidapi https://rapidapi.com
2. then on the apihub search for OmadaVoucherAPI or click this link https://rapidapi.com/mcandres888-0d-S2XDAipF/api/omadavoucherapi/
3. you can go to pricing to check the pricing
    basic = free 5 calls / day
    pro = $1 per month , 100  calls / day
    ultra (promo) = $5 per month , 1000 calls / day - multi site

4. once you subscribe to a plan ( you can start with basic first to test the functionality )
5. go to endpoint , then click the register ( this will register your omada cloud controller with that site )
     - and edit the body schema , site name will be exact name of the site - please make sure of spaces and capital letter are the same
   ```
     {
      "omadahost": "https://youromadaurlhere.com",
      "omadauser": "yourusername",
      "omadapass": "yourpassword",
      "site": "site name"
    }
   ```
     - this will return an id ( please take note of this id as we will use this on the site mapping )
     - you can also check your accounts by accessing the accounts endpoint
6. Clone this repository and rename it to <username>.github.io  - if you want to host this html for free on github
7. edit index.html to your liking. on line 306 , add your apikey ( from rapidapi )
8. on line 175 edit the site map and add your account id ( the one that was returned from register endpoint ) and give it a name.
9. you can now test by accessing your url with the sitename on the sitemap  <username>.github.io?site=<sitename>
10. you can also convert this into qr code and add it to your voucher tickets -> https://qrfy.com

please message me on m.me/arclem888 if you want other features
ENJOY!
