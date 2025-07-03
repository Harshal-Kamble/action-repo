<h1>GitHub Action Repo (Triggers Webhook)</h1>

<p>This repository is used to trigger webhook events (push and pull request) for testing a webhook receiver application.</p>

<h2>🔁 What This Repo Does</h2>
<ul>
  <li>Trigger GitHub events like push and pull request</li>
  <li>Send those events to the Flask webhook endpoint:</li>
</ul>
<pre><code>https://your-ngrok-url.ngrok-free.app/webhook</code></pre>

<p>The backend stores it in MongoDB and the frontend displays it live.</p>

<h2>🚀 How to Use</h2>
<ol>
  <li>Clone this repo</li>
  <li>Push new commits or create pull requests</li>
  <li>Flask app receives the events and displays them on:
    <br><code>http://localhost:5000</code></li>
</ol>

<h2>📎 Example Events</h2>
<ul>
  <li>Harshal pushed to main on 4th July 2025 - 5:15 PM UTC</li>
  <li>Harshal submitted a pull request from dev to main on 4th July 2025 - 6:05 PM UTC</li>
</ul>

<h2>🔗 Related Repo</h2>
<p><a href="https://github.com/Harshal-Kamble/webhook-repo">Webhook Receiver & UI Repo</a></p>

<h2>🧑‍💻 Author 🧑‍💻</h2>
<p><strong>Harshal Kamble</strong><br>
<a href="https://github.com/Harshal-Kamble">GitHub Profile</a></p>
