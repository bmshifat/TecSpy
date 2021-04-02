<p align="center" ><img class="aligncenter" src="https://raw.githubusercontent.com/bmshifat/TecSpy/main/assets/webpublic/favicon.png" alt="" width="116" height="113" /></p>
<p align="center" > A cloud-based Android Monitoring Tool, powered by NodeJS</p>

<h2>Features</h2>
<ul>
 	<li>GPS Logging</li>
 	<li>Microphone Recording</li>
 	<li>View Contacts</li>
 	<li>SMS Logs</li>
 	<li>Call Logs</li>
 	<li>View Installed Apps</li>
 	<li>View Stub Permissions</li>
 	<li>Live Clipboard Logging</li>
 	<li>Live Notification Logging (WhatsApp, Facebook, Instagram, Gmail, and more ....)</li>
 	<li>View WiFi Networks (logs previously seen)</li>
 	<li>File Explorer &amp; Downloader</li>
 	<li>Command Queuing</li>
 	<li>Device Admin</li>
</ul>
<h2>Prerequisites</h2>
<ul>
 	<li>NodeJs</li>
 	<li>A Server with Static IP Address</li>
</ul>
<h2>Installation</h2>
In the extracted folder, run these commands
<ul>
 	<li style="list-style-type: none;">
<ul>
 	<li><code>npm install</code> &lt;- install dependencies</li>
 	<li><code>npm start</code> &lt;-- start the script</li>
 	<li>In your browser navigate to your Server Static IP Address<code> Ex.: http://127.0.0.1</code></li>
</ul>
</li>
</ul>
<h2>Or to Run It on Background</h2>
<ul>
 	<li><code>npm install</code> &lt;- install dependencies</li>
 	<li><code>pm2 start index.js</code> &lt;-- start the script</li>
 	<li><code>pm2 startup</code> &lt;- to run TecSpy on startup</li>
 	<li>In your browser navigate to your Server Static IP Address<code> Ex.: http://127.0.0.1</code></li>
</ul>
<h3>Set a Username &amp; Password</h3>
<ol>
 	<li>Open <code>maindb.json</code> in a text editor</li>
 	<li>under <code>admin</code>
<ul>
 	<li>set the <code>username</code> as plain text</li>
 	<li>set the <code>password</code> as a LOWERCASE MD5 hash</li>
</ul>
</li>
 	<li>save the file</li>
 	<li>Now <code>restart the app</code></li>
</ul>
</ol>
&nbsp;
<h2>Credits</h2>
Credits for the original code base this repository is based on at<b> <a href="https://github.com/D3VL/L3MON">L3MON</a></b>

