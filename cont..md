# Cont.

INorder to keep the encryption keys and other related stuffs private , install &lt;&lt; **npm install dotenv** &gt;&gt;

{% hint style="info" %}
[https://www.npmjs.com/package/dotenv](https://www.npmjs.com/package/dotenv)
{% endhint %}

![](.gitbook/assets/image%20%2833%29.png)

Eventhough the secrets are in the  .env file , while uploading it into a remote repository,it is revealed, for that use &lt;&lt; **.gitignore** &gt;&gt;

{% hint style="info" %}
[https://github.com/github/gitignore](https://github.com/github/gitignore)

[https://github.com/github/gitignore/blob/master/Node.gitignore](https://github.com/github/gitignore/blob/master/Node.gitignore)
{% endhint %}

In case of deploying the code,those gitignore files are required for proper functioning of app....

{% hint style="info" %}
[https://devcenter.heroku.com/categories/deployment](https://devcenter.heroku.com/categories/deployment)

[https://devcenter.heroku.com/articles/config-vars](https://devcenter.heroku.com/articles/config-vars) &lt;&lt;refer this link for the below dropped pic &gt;&gt;
{% endhint %}

![](.gitbook/assets/image%20%2841%29.png)

### 🐞 HASHING PASSWORDS

hashing is a mathematical eq. that makes almost **impossible to go back** to Password.

![](.gitbook/assets/image%20%2843%29.png)

![](.gitbook/assets/image%20%2847%29.png)

![](.gitbook/assets/image%20%285%29.png)

1. Install  &lt;&lt; **npm i md5** &gt;&gt;
2. 
![](.gitbook/assets/image%20%2832%29.png)

The password entered by the user is changed using the hash function by the help of the installed package &lt;&lt;**npm i md5** &gt;&gt;  and stored in the DB.

![](.gitbook/assets/image%20%282%29.png)

At the Login page ,if the user enters the correct password then the entered password in the registration is compared with the password in login ...If correct then it goes into the page requested.

### 🐞 HACKING PASSWORDS

{% hint style="info" %}
[https://haveibeenpwned.com/](https://haveibeenpwned.com/) 
{% endhint %}

![Hash Table](.gitbook/assets/image%20%2818%29.png)

![](.gitbook/assets/image%20%2848%29.png)

![](.gitbook/assets/image%20%2831%29.png)

{% hint style="info" %}
[http://password-checker.online-domain-tools.com/](http://password-checker.online-domain-tools.com/)
{% endhint %}

## 🐞 LEVEL 4

#### 👒 HASHING AND SALTING

Prevents Dictionary attacks and Hash table cracks

![](.gitbook/assets/image%20%284%29.png)

### Example

![](.gitbook/assets/image%20%2836%29.png)

#### bcrypt is a slow

#### SALT ROUNDS

The rounds of salt added to the password to make it more complex for the users to hack.

![](.gitbook/assets/image%20%2812%29.png)

![](.gitbook/assets/image%20%2835%29.png)

The more the number of rounds ,increases the complexity and security of password.Install &lt;&lt;npm i bcrypt&gt;&gt;

{% hint style="info" %}
[https://github.com/kelektiv/node.bcrypt.js/blob/master/README.md](https://github.com/kelektiv/node.bcrypt.js/blob/master/README.md)
{% endhint %}

![](.gitbook/assets/image%20%286%29.png)

For Login

![](.gitbook/assets/image%20%2813%29.png)

