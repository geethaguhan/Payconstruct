<h1>Payconstruct</h1>

Assessment
<br/>
#Install node 
<br/>
#Unrar Payconstruct folder and upload into node installed folder
<br/>
#Run following command on command line<b>npm run start</b>
<br/>
#Use Postman to test api
<br>
<h4>Api lists</h4>

#To display customer list use below api
<br/>
http://localhost:2000 
<br/>Use Get method to display result.
<br/>
<br/>
#To serach customer by id use below api
<br>
http://localhost:2000/search/1
<br/>Use Get method to display result.
<br/>
<br/>
To add new customer use below link
<br/>
http://localhost:2000/create
<br/>
Use post method and pass following json in body
<pre>
{
    "id": 5,
    "name": "Peter Jhon",
    "deposit": 10000,
    "balance": 10000
}
</pre>
<br/>
To get transaction list by coustmer id use below link  and use get method.
<br/>
http://localhost:2000/transaction/1
</br>
</br>
#to transper amount to another coustomer use below link
<br/>

</br>
Use below json input on body and use post method
<br/>
http://localhost:2000/transfer
<br/>
<pre>
{
    "id": 5,
    "fromcid": 1,
    "tocid": 4,
    "amount": 12000,
    "date": "5/aug/2018"
}

</pre>

