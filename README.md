# V2ray for Replit
- Made into english by unblockedtutorials 😎
- Create By xiaowansm<br>
- Modlfy By ifeng<br>
- Web Site: https://www.hicairo.com <br>
- Telegram: https://t.me/HiaiFeng <br>

- Note replit wont be free in January 1st 2024 😞

Introduction:
This project is used to deploy V2ray on the Replit.com free service. The solution adopted is Nginx + WebSocket + VMess/VLess + TLS.
# Precautions:
<b>Please do not abuse, account ban will be at your own risk. Network traffic is 10GB per month. </b>
# Deployment:
<p>Log in to the <a href="https://replit.com">Replit.com</a> account, select Bash for Template, fill in any Title, and create an instance. </p>
<img src="https://www.hicairo.com/zb_users/upload/2022/12/202212221671676417413561.webp">
<p>Use the following link to download the file locally and decompress it, then upload the decompressed file. You can select all and drag them into the Files box. </p>
<p>https://github.com/hiifeng/V2ray-for-Replit/raw/main/V2ray-for-Replit.zip</p>
<img src="https://hicairo.com/zb_users/upload/2023/02/202302131676266061661306.webp">
<p>Wait for the file upload to complete, which will take about 2 minutes. When Overwrite file appears, select Yes to overwrite this file. </p>
<img src="https://hicairo.com/zb_users/upload/2022/12/202212291672276356316990.webp?">

# Instructions:
<p>After clicking the Run button at the top, the service will run automatically. Then copy the VMess/VLess protocol link in the console window and import it into the client software. Or use mobile client software to scan the QR code of the VMess/VLess protocol. </p>

<p><b>UUID (User ID) or disguised path in custom node:</b></p>
<p>Since UUID uses the REPL_ID variable provided by the Replit platform by default, each instance UUID is unique and will not be known to others, and there will be no node information leakage problem. Therefore, customizing information such as UUID is of little significance. If you really want to make changes, please refer to the following steps:</p>
<p>1. Use a third-party tool (https://www.v2fly.org/awesome/tools.html) to generate a new UUID. </p>
<p>2. Click the Secrets button in the Tools menu on the left. Add three system variables. The key values ​​are</p>
"UUID", "VMESS_WSPATH" and "VLESS_WSPATH". </p>
The value values ​​are "UUID generated using third-party tools", "vmess camouflage path" and "vless camouflage path". </p>
<p>3. Note: The values ​​of "VMESS_WSPATH" and "VLESS_WSPATH" need to start with the "/" symbol. </p>
<pre class="notranslate"><code># example:
UUID de04add9-5c68-8bab-950c-08cd5320df18
VMESS_WSPATH/vm
VLESS_WSPATH /vl
</code></pre>

# Feedback and communication:
If you encounter any problems during use, please contact me using Telegram. (https://t.me/HiaiFeng)
