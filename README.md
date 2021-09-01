<h1>Payconstruct</h1>

Assessment
<br/>
#Install node 
<br/>
#Unrar Payconstruct folder and upload into node installed folder
<br/>
#Run following command on command line <b>npm run start</b>
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
#To add new customer use below api
<br/>
http://localhost:2000/create
<br/>
Use post method and pass following json in body
<div>
<pre>
<code>
{
    "id": 5,
    "name": "Peter Jhon",
    "deposit": 10000,
    "balance": 10000
}
</code>
</pre>
 <div>
#To get transaction list by coustmer id use below api and use get method.
<br/>
<a href="http://localhost:2000/transaction/1" rel="nofollow">http://localhost:2000/transaction/1</a>        
</br>
<br/>
#To transper amount to another coustomer use below api and use post method
<br/>
Use below json input on body and use post method
<br/>

<a href="http://localhost:2000/transfer" rel="nofollow">http://localhost:2000/transfer</a>  
<pre>
<code>
{
    "id": 5,
    "fromcid": 1,
    "tocid": 4,
    "amount": 12000,
    "date": "5/aug/2018"
}
</code>
</pre>
