<h1>Video Streaming Server and Client</h1>
<p>This repository contains a simple video streaming server and client application. This application streams video over UDP (User Datagram Protocol) communication between the server and the client.</p>

<h2>Requirements</h2>
<ul>
    <li>Python 3.x</li>
    <li>OpenCV (<code>pip install opencv-python</code>)</li>
    <li>NumPy (<code>pip install numpy</code>)</li>
    <li>imutils (<code>pip install imutils</code>)</li>
</ul>

<h2>Server</h2>
<p>The server side captures video from a camera device, compresses it, and sends it to the client.</p>
<p>To run the server:</p>
<pre><code>python server.py</code></pre>

<h2>Client</h2>
<p>The client side receives the video stream from the server and displays it on the screen.</p>
<p>To run the client:</p>
<pre><code>python client.py</code></pre>

<h2>How it Works?</h2>
<ol>
    <li>Start the server and the client.</li>
    <li>The server captures video from the camera, compresses it, and sends it to the client.</li>
    <li>The client receives the video stream from the server and displays it on the screen.</li>
</ol>
