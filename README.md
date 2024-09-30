<h1>Civil Advocacy App</h1>

<p>This Android app fetches and displays a list of political officials representing a user's current location (or a specified location) across different levels of government. The app uses the <a href="https://developers.google.com/civic-information">Google Civic Information API</a> to retrieve data about government officials and allows users to explore detailed information about their representatives.</p>

<h2>Features</h2>
<ul>
  <li>Acquires and displays political officials based on the user's current location or a specified location.</li>
  <li>Uses <strong>Fused Location Provider</strong> to determine the user's location.</li>
  <li>Fetches government official data using <a href="https://developers.google.com/civic-information">Google Civic Information API</a> via RESTful services.</li>
  <li>Supports both portrait and landscape orientations with distinct layouts for 2 key activities.</li>
  <li>Clicking on a government official’s entry shows detailed information about that official.</li>
  <li>Displays a larger version of the official’s photo when the image is clicked.</li>
  <li>An “About” page includes app author information, copyright, and version details.</li>
</ul>

<h2>Technologies Used</h2>
<ul>
  <li><strong>Android Studio</strong> - Development environment.</li>
  <li><strong>Java</strong> - Programming language.</li>
  <li><strong>Fused Location Provider</strong> - To determine the user’s current location.</li>
  <li><strong>Google Civic Information API</strong> - For retrieving government official information.</li>
  <li><strong>Picasso Library</strong> - For handling and displaying images of the officials.</li>
  <li><strong>Implicit Intents</strong> - For navigating between activities and external content (e.g., browser).</li>
  <li><strong>TextView Links</strong> - Clickable links within TextViews to navigate to websites or external resources.</li>
  <li><strong>Location Services</strong> - For accessing user location data.</li>
  <li><strong>Internet</strong> - For accessing the RESTful API and fetching data.</li>
</ul>

<h2>Setup and Installation</h2>
<ol>
  <li>Clone the repository:
    <pre><code>git clone https://github.com/RikGanguli/Android-Civil-Advocacy-App.git</code></pre>
  </li>
  <li>Open the project in Android Studio.</li>
  <li>Ensure you have the required dependencies in your <code>build.gradle</code> file (e.g., Fused Location Provider, Picasso, etc.).</li>
  <li>Add the necessary permissions in the AndroidManifest.xml:
    <pre><code>&lt;uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" /&gt;
&lt;uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" /&gt;
&lt;uses-permission android:name="android.permission.INTERNET" /&gt;
    </code></pre>
  </li>
  <li>Get an API key for the <a href="https://developers.google.com/civic-information">Google Civic Information API</a> and add it to your project.</li>
  <li>Run the app on an Android device or emulator.</li>
</ol>

<h2>API Setup</h2>
<ol>
  <li>Sign up for an API key from <a href="https://developers.google.com/civic-information">Google Civic Information API</a>.</li>
  <li>Add your API key in GetPoliticianData.java.</li>
</ol>

<h2>Usage</h2>
<ul>
  <li>Upon launch, the app will request permission to access the user’s location.</li>
  <li>Once location access is granted, the app will display political officials representing the current location.</li>
  <li>Users can click on an official to view detailed information, including their name, position, contact details, and photo.</li>
  <li>Clicking the official’s photo opens a new activity showing a larger version of the image.</li>
  <li>Users can view the app's "About" page to see information about the developer, version, and copyright.</li>
</ul>

<h2>Screenshots</h2>
<p></p>

<h2>Credits</h2>
<p>Developed by Rik Ganguli Biswas</p>
<p>Powered by <a href="https://developers.google.com/civic-information">Google Civic Information API</a> and <a href="https://square.github.io/picasso/">Picasso Library</a>.</p>
