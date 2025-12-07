<h1 align="center">🌐 NetPractice — 42 Project</h1>

<p align="center">
  <!-- Badges -->
  <img src="https://img.shields.io/badge/Project-42_NetPractice-2ea44f?style=for-the-badge">
  <img src="https://img.shields.io/badge/Language-Networking-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Level-Beginner%20to%20Intermediate-yellow?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
</p>

<p align="center">
  A training project to learn the fundamentals of computer networking,<br>
  IP addressing, subnetting, routing logic, and network troubleshooting.
</p>

<hr>

<h2>📌 Overview</h2>
<p>
  <strong>NetPractice</strong> is an interactive network configuration project required in the 42 curriculum.
  It teaches core networking concepts through problem-solving exercises where you must fix and configure
  various network topologies.  
</p>

<p>
  This project is essential for understanding how IP addresses, masks, routers, NAT, and routing tables work.
  Every level is a network puzzle that must be solved to make all machines communicate.
</p>

<hr>

<h2>🎯 Objectives</h2>
<ul>
  <li>Understand IPv4 addressing and subnet masks.</li>
  <li>Learn how routing works between networks.</li>
  <li>Configure interfaces, routers, and NAT correctly.</li>
  <li>Analyze connectivity and troubleshoot using logic.</li>
  <li>Apply CIDR notation properly.</li>
</ul>

<hr>

<h2>📁 Project Structure</h2>
<p>The project consists of multiple <strong>levels</strong>, each containing:</p>
<ul>
  <li>A network diagram</li>
  <li>Interfaces with missing or incorrect configurations</li>
  <li>Routing tables to fix</li>
  <li>Connectivity goals to achieve</li>
</ul>

<p>Your task is to make all nodes communicate successfully.</p>

<hr>

<h2>🧠 Key Concepts You Must Master</h2>
<ul>
  <li><strong>IP Addressing</strong> (IPv4)</li>
  <li><strong>Subnet Masks</strong> & CIDR (e.g. /24, /30, /16)</li>
  <li><strong>Subnetting & Supernetting</strong></li>
  <li><strong>Network / Broadcast addresses</strong></li>
  <li><strong>Routing Tables</strong> & next-hop logic</li>
  <li><strong>NAT</strong> (Network Address Translation)</li>
  <li><strong>Static routing</strong></li>
</ul>

<hr>

<h2>🧩 Example Exercise (Simplified)</h2>

<p>Given two PCs:</p>
<ul>
  <li>PC1: 192.168.1.10 / 24</li>
  <li>PC2: 192.168.2.5 / 24</li>
</ul>

<p>They cannot communicate. Why?</p>

<p><strong>Solution:</strong> They are in different networks (/24).  
You must add a router between them and configure routes.</p>

<hr>

<h2>🚀 How to Use NetPractice</h2>
<ol>
  <li>Open the exercises in the 42 intranet.</li>
  <li>Study the network topology.</li>
  <li>Assign correct IPs & subnet masks to each interface.</li>
  <li>Fix or complete routing tables.</li>
  <li>Validate connectivity after each change.</li>
</ol>

<p><strong>Tip:</strong> Always check network address & broadcast address first —  
99% of errors come from incorrect subnet boundaries.</p>

<hr>

<h2>📚 Helpful Subnetting Cheatsheet</h2>

<table>
  <tr><th>CIDR</th><th>Mask</th><th>Hosts</th></tr>
  <tr><td>/30</td><td>255.255.255.252</td><td>2 hosts</td></tr>
  <tr><td>/29</td><td>255.255.255.248</td><td>6 hosts</td></tr>
  <tr><td>/28</td><td>255.255.255.240</td><td>14 hosts</td></tr>
  <tr><td>/24</td><td>255.255.255.0</td><td>254 hosts</td></tr>
</table>

<hr>

<h2>💡 Tips for Passing All Levels</h2>
<ul>
  <li>Write down the network address and broadcast for every subnet.</li>
  <li>Ensure no two interfaces share the same IP.</li>
  <li>Routers must have one IP per connected network.</li>
  <li>Every route must point toward a reachable next hop.</li>
  <li>For NAT levels, check which interface is the “public” one.</li>
</ul>

<hr>

<h2>📝 Final Thoughts</h2>
<p>
  NetPractice is less about memorization and more about logical thinking.  
  Once you fully understand IP partitioning and routing, the levels become intuitive.
</p>

<hr>

<h2>📄 License</h2>
<p>
  This repository follows the 42 school guidelines and does not contain the official exercises.
  Only personal documentation and explanations are provided.
</p>

<hr>

<h3 align="center">⭐ If this helped you, consider giving the repo a star!</h3>
