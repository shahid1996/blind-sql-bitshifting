# Blind SQL Injection via Bitshifting
This is a module written for the **WHFramework**.

It performs blind SQL injection by using the bitshifting method to calculate chars instead of guessing them. It requires exactly 8 requests per character.

Method by **Jelmer de Hen** (https://www.exploit-db.com/papers/17073/)

Coded by **Eclipse** of **Team Salvation** (http://ljdbosgro7jj4z7r.onion)

##Usage
```
import blind-sql-bitshifting as x

x.options #edit this to edit options
```

Then:

`x.exploit()`

This returns a 2-dimentional array, with each sub-array containing a single row, the first being the column headers.

Example output:

`[['id', 'username'], ['1', 'lol'], ['2', 'lel']]`
