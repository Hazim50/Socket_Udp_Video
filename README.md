<h1>[EN]</h1>
<h2>Video Streaming Server and Client</h2>
<p>This repository contains a simple video streaming server and client application. This application streams video over UDP (User Datagram Protocol) communication between the server and the client.</p>

<h3>Requirements</h3>
<ul>
    <li>Python 3.x</li>
    <li>OpenCV (<code>pip install opencv-python</code>)</li>
    <li>NumPy (<code>pip install numpy</code>)</li>
    <li>imutils (<code>pip install imutils</code>)</li>
</ul>

<h3>Server</h3>
<p>The server side captures video from a camera device, compresses it, and sends it to the client.</p>
<p>To run the server:</p>
<pre><code>python server.py</code></pre>

<h3>Client</h3>
<p>The client side receives the video stream from the server and displays it on the screen.</p>
<p>To run the client:</p>
<pre><code>python client.py</code></pre>

<h3>How it Works?</h3>
<ol>
    <li>Start the server and the client.</li>
    <li>The server captures video from the camera, compresses it, and sends it to the client.</li>
    <li>The client receives the video stream from the server and displays it on the screen.</li>
</ol>

<h1>[TR]</h1>
<h2>Video Akış Sunucusu ve İstemcisi</h2>
<p>Bu depo, basit bir video akışı sunucusu ve istemci uygulamasını içerir. Bu uygulama, sunucu ile istemci arasında UDP (Kullanıcı Verigramı Protokolü) iletişimi üzerinden video akışı sağlar.</p>

<h3>Gereksinimler</h3>
<ul>
    <li>Python 3.x</li>
    <li>OpenCV (<code>pip install opencv-python</code>)</li>
    <li>NumPy (<code>pip install numpy</code>)</li>
    <li>imutils (<code>pip install imutils</code>)</li>
</ul>

<h3>Sunucu</h3>
<p>Sunucu tarafı, bir kamera cihazından video yakalar, sıkıştırır ve istemciye gönderir.</p>
<p>Sunucuyu çalıştırmak için:</p>
<pre><code>python server.py</code></pre>

<h3>İstemci</h3>
<p>İstemci tarafı, sunucudan gelen video akışını alır ve ekranda görüntüler.</p>
<p>İstemciyi çalıştırmak için:</p>
<pre><code>python client.py</code></pre>

<h3>Nasıl Çalışır?</h3>
<ol>
    <li>Sunucuyu ve istemciyi başlatın.</li>
    <li>Sunucu, kameradan video yakalar, sıkıştırır ve istemciye gönderir.</li>
    <li>İstemci, sunucudan gelen video akışını alır ve ekranda görüntüler.</li>
</ol>
