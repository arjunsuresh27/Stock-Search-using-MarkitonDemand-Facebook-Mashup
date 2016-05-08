# Stock-Search-using-MarkitonDemand-Facebook-Mashup
This project aims at developing an web rich Stock search Engine application, that fetches comprehensive details of all the companies listed in US stock exchange. Developed using latest technologies like HTML5, CSS3, PHP, JSON, responsive web site using boot strap, JQUERY, javascript, Amazon AWS Elastic bean EC2 etc.

Description- 

A user will first open a page the stock search home page, where he/she can enter the company name or symbol, and select from a list using autocomplete. A quote on a matched stock symbol can be performed. The description of the form is given in section 4.1. Instructions on how to use the API are given in section, Once the user has provided data and selected a result from the autocomplete list he would  click on Get Quote, when validation must be done to check that the entered data is valid. 
Once the validation is successful, the JQuery function ajax() is executed to start an asynchronous transaction with a PHP script  running on Amazon Web Services, and passing the search form data as parameters of the transaction. The php script returnes JSON formatted data from the API to the search webpage. The webpage must then use JavaScript to extract data from the JSON and display the results on the same webpage.

The sample of the working stock search engine can be found at - http://cs-server.usc.edu:11082/first_bootstrap.html
