<h1 align="center">💬 Real-Time Chat Application</h1>

<p align="center">
  <b>A modern real-time chat app built with React 19 & Socket.IO</b>
</p>

<p align="center">
  🔐 Authentication • 💬 Realtime Messaging • ⚡ Fast & Scalable
</p>

<hr/>

<h2>🚀 Features</h2>

<ul>
  <li>🔐 <b>User Authentication</b> (Login & Signup)</li>
  <li>💬 <b>Real-time Messaging</b> using Socket.IO</li>
  <li>🧠 <b>Global State Management</b> with Zustand</li>
  <li>🔔 <b>Instant Notifications</b> using React Hot Toast</li>
  <li>🧭 <b>Client-side Routing</b> with React Router v7</li>
  <li>🎨 <b>Modern UI</b> with Lucide Icons</li>
  <li>🌐 <b>API Communication</b> using Axios</li>
</ul>

<hr/>

<h2>🛠️ Tech Stack</h2>

<table>
  <tr>
    <th align="left">Category</th>
    <th align="left">Technology</th>
  </tr>
  <tr>
    <td>Frontend</td>
    <td>React 19, React DOM</td>
  </tr>
  <tr>
    <td>Routing</td>
    <td>React Router v7</td>
  </tr>
  <tr>
    <td>State Management</td>
    <td>Zustand</td>
  </tr>
  <tr>
    <td>Realtime</td>
    <td>Socket.IO Client</td>
  </tr>
  <tr>
    <td>HTTP Client</td>
    <td>Axios</td>
  </tr>
  <tr>
    <td>UI & Icons</td>
    <td>Lucide React</td>
  </tr>
  <tr>
    <td>Notifications</td>
    <td>React Hot Toast</td>
  </tr>
</table>

<hr/>

<h2>📦 Dependencies</h2>

<pre>
axios ^1.13.2
lucide-react ^0.562.0
react ^19.2.3
react-dom ^19.2.3
react-hot-toast ^2.6.0
react-router ^7.11.0
socket.io-client ^4.8.3
zustand ^5.0.9
</pre>

<hr/>

<h2>📂 Project Structure</h2>

<pre>
src/
│
├── api/              → Axios API handlers
├── components/       → Reusable UI components
├── pages/            → Route-based pages
├── store/            → Zustand global stores
├── socket/           → Socket.IO client setup
├── routes/           → Application routes
├── hooks/            → Custom React hooks
├── utils/            → Helper functions
├── App.jsx
└── main.jsx
</pre>

<hr/>

<h2>⚙️ Installation</h2>

<h4>1️⃣ Clone the repository</h4>

<pre>
git clone https://github.com/BiplobSordar/chatify-client.git
cd chatify-client
</pre>

<h4>2️⃣ Install dependencies</h4>

<pre>
npm install
</pre>

<h4>3️⃣ Start development server</h4>

<pre>
npm run dev
</pre>

<hr/>

<h2>🔐 Authentication Flow</h2>

<ol>
  <li>User registers or logs in</li>
  <li>Authentication token is stored on the client</li>
  <li>Axios attaches token to every protected request</li>
  <li>Protected routes handled via React Router</li>
</ol>

<hr/>

<h2>🔌 Realtime Communication</h2>

<ul>
  <li>Persistent WebSocket connection via Socket.IO</li>
  <li>Instant message delivery</li>
  <li>Automatic UI updates on new messages</li>
</ul>

<hr/>

<h2>🌍 Environment Variables</h2>

<pre>
VITE_API_URL=http://localhost:5000/api
VITE_SOCKET_URL=http://localhost:5000
</pre>

<hr/>

<h2>🚧 Future Enhancements</h2>

<ul>
  <li>✅ Online / Offline user status</li>
  <li>📎 File & Image sharing</li>
  <li>🧑‍🤝‍🧑 Group chat</li>
  <li>🔒 End-to-end encryption</li>
</ul>

<hr/>

<h2>👨‍💻 Author</h2>

<p>
  <b>Biplob Sordar</b><br/>
  Full Stack Developer (MERN)<br/><br/>
  🔗 GitHub: <a href="https://github.com/BiplobSordar">Biplob Sordar</a><br/>
  🔗 LinkedIn: <a href="www.linkedin.com/in/biplob-sordar">Biplob Sordar</a>
</p>

<hr/>

<p align="center">
  ⭐ If you like this project, please give it a star!
</p>
