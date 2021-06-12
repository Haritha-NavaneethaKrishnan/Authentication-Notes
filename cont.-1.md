# Cont.

## 🐞 LEVEL 5

### Cookies and Session

1. When a user,goes to  a shopping page -- &gt; he makes a get request to tha server
2. The server inturn sends the requested page \(html,css n js files\)
3. The user then adds an item to the cart and gets destracted.
4. That stored item in cart is saved as cookie in the server.
5. So next time,when user tries to access, the cookie is used for fast access as well as keep remind of what was selected

#### 👒 Session Cookies

After the particular time limit,the cookie is destroyed

#### 👒 Passport

For the purpose of authentication by adding Google etc

![](.gitbook/assets/image%20%2823%29.png)

{% hint style="info" %}
[http://www.passportjs.org/docs/](http://www.passportjs.org/docs/)

[https://www.npmjs.com/package/passport-local-mongoose](https://www.npmjs.com/package/passport-local-mongoose)
{% endhint %}

#### For Register

![](.gitbook/assets/image%20%289%29.png)

![](.gitbook/assets/image%20%2820%29.png)

#### For Login

![](.gitbook/assets/image%20%2825%29.png)

```text
If the authentication is successful , then the user is redirected to the requested page and a cookie is created ,until the brower is closed ,the cookie is live.This is the main advantage of *Passport*
```



