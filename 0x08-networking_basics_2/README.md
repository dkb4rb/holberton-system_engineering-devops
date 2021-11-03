<h1 class="gap">0x08. Networking basics #1</h1>
<h2>Resources</h2>

<p><strong>Read or watch</strong>:</p>

<ul>
<li><a href="/rltoken/7SedZ8ILSQulYf7xzSbraQ" title="What is localhost" target="_blank">What is localhost</a> </li>
<li><a href="/rltoken/n5IFAt_OWGJtGW33t7Jfag" title="What is 0.0.0.0" target="_blank">What is 0.0.0.0</a> </li>
<li><a href="/rltoken/21l3Uqizr3LpA1ZGrYPg3g" title="What is the hosts file" target="_blank">What is the hosts file</a> </li>
<li><a href="/rltoken/uMleIIzkRoR2w8EkwItSEg" title="Netcat examples" target="_blank">Netcat examples</a> </li>
</ul>

<p><strong>man or help</strong>:</p>

<ul>
<li><code>ifconfig</code></li>
<li><code>telnet</code></li>
<li><code>nc</code></li>
<li><code>cut</code></li>
</ul>

<h2>Learning Objectives</h2>

<p>At the end of this project, you are expected to be able to <a href="/rltoken/BxPpO9moponw8J8TjKpRlg" title="explain to anyone" target="_blank">explain to anyone</a>, <strong>without the help of Google</strong>:</p>

<h3>General</h3>

<ul>
<li>What is localhost/127.0.0.1</li>
<li>What is 0.0.0.0</li>
<li>What is <code>/etc/hosts</code></li>
<li>How to display your machine&rsquo;s active network interfaces</li>
</ul>

<h2>Requirements</h2>

<h3>General</h3>

<ul>
<li>Allowed editors: <code>vi</code>, <code>vim</code>, <code>emacs</code></li>
<li>All your files will be interpreted on Ubuntu 20.04 LTS</li>
<li>All your files should end with a new line</li>
<li>A <code>README.md</code> file, at the root of the folder of the project, is mandatory</li>
<li>All your Bash script files must be executable</li>
<li>Your Bash script must pass <code>Shellcheck</code> (version <code>0.7.0</code> via <code>apt-get</code>) without any errors</li>
<li>The first line of all your Bash scripts should be exactly <code>#!/usr/bin/env bash</code></li>
<li>The second line of all your Bash scripts should be a comment explaining what is the script doing</li>
</ul>

</div>

# Networking basics #2

This project was the second of two introducing networking. I continued to learn
about IP addresses while practicing manipulating them with Bash scripts.

## Tasks :page_with_curl:

* **Localhost**
  * [0-localhost](./0-localhost): Text file that answers the following question:
  * What is `localhost`?
    1. A hostname that means this IP
    2. A hostname that means this computer
    3. An IP attached to a computer

* **1. All IPs**
  * [1-wildcard](./1-wildcard): Text file that answers the following question:
  * What is `0.0.0.0`?
    1. All IPv4 addresses on the local machine
    2. All the IPs
    3. It means null in networking

* **2. Change your home IP**
  * [2-change_your_home_IP](./2-change_your_home_IP): Bash script that configures
  an Ubuntu server as follows:
  * `localhost` resolves to `127.0.0.2`
  * `facebook.com` resolves to `8.8.8.8`

* **3. Show attached IPs**
  * [3-show_attached_IPs](./3-show_attached_IPs): Bash script that displays all active IPv4
  IP's on the machine.

* **4. Port listening on localhost**
  * [4-port_listening_on_localhost](./4-port_listening_on_localhost): Bash script that
  listens on port `98` on `localhost`.