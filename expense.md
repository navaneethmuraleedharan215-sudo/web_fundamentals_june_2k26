Expenses

id  owner    amount   category  payment_method

1   balan     500      tea       cash
2   ajay      570      rent       upi
3   jithn     654      food      bank transfer
4   rahul     700      medical   bank transfer

```

```
http_request for adding expense

url: localhost:8000/expense/
method:POST
body:{
    "owner":"rudru",
    "amount":890,
    "category":"shopping",
    "payment_method":"card"
}



```
---
```
http_request for listing expense

url:localhost:8000/expense/
method:GET

```

---
```
http_request for fetching specific expense detail

url : localhost:8000/expense/4/
method:GET

```

```
http_request for updating an expense

url:localhost:8000/expense/4/
method:PUT
body:{
    "owner":"nandhana",
    "amount":880,
    "category":"shopping",
    "payment_method":"card"
}

```

```
http_request for deleting  specific expense 

url:localhost:8000/expense/4/
method:DELETE
```