<h1 align="center">Welcome to Hookup 💻 </h1>
<p>
  <a href="#" target="_blank">
    <img alt="License: MIT" src="https://cdn.discordapp.com/attachments/935662572814880848/937270823922827305/logo.png" />
  </a>
</p>

> New generation phishing tool.

A phishing tool that is written in Python and VueJS

## Installation 📀

### Step 1
---
Launch your terminal

```bash
λ git clone https://github.com/0bf/hookup
λ cd hookup
```

Install dependencies with `pip`

```bash
λ pip install -r requirements.txt
```


### Step 2
---

Run phishing and GUI server. If you have never launched the program before, it will ask for username and password.

```
λ python run.py
Username: ruin
Password
[+] Done
 * Serving Flask app "hookup" (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: on
 * Restarting with stat
```

If everything is ok, you'll see the ngrok page which is shown below
![img](https://i.imgyukle.com/2020/01/31/nPcXnQ.png)

And now, open your favorite browser then type  `http://localhost:5000/adminpage` for the control panel.

## Usage 👨‍💻
---

![img](https://i.imgyukle.com/2020/01/31/nPgm0I.png)

Login with your username and password (you set them on step 2)

#### Configure
![img](https://i.imgyukle.com/2020/01/31/nPi1nb.png)

On the configuration panel, you'll see that some fake pages have been already set up. Select the one for your use. "Current Page" part contains the data that victim will see.

### Results
![img](https://i.imgyukle.com/2020/01/31/nPpodU.png)
The ngrok URL publishes your local server to the internet. You can get your fake page's URL at the top right corner of the screen(the part which says "Ngrok Url: ".). If your victim types their credientals correctly and pushes the send button, you'll handle the POST payload and results will be shown like the image above.



## Author

👤 **ruin**

* Website: http://ruin.vip
* Twitter: [ruin#1337](https://discord.com/users/915698757478273115)
* Github: [@0bf](https://github.com/0bf)

## Show your support

Give a ⭐️ if this project helped you!

***
