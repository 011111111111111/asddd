<!DOCTYPE html>
<html>
<head>
  <title>Chat App</title>
  <style>
    body { font-family: Arial; }
    #messages { list-style: none; padding: 0; }
    #messages li { padding: 5px 10px; }
    #form { display: flex; margin-top: 10px; }
    #input { flex: 1; padding: 10px; }
    #send { padding: 10px; }
  </style>
</head>
<body>
  <h2>Simple Chat App</h2>
  <ul id="messages"></ul>
  <form id="form">
    <input id="input" autocomplete="off" placeholder="Type your message..." /><button id="send">Send</button>
  </form>

  <script src="/socket.io/socket.io.js"></script>
  <script>
    const socket = io();

    const form = document.getElementById('form');
    const input = document.getElementById('input');
    const messages = document.getElementById('messages');

    form.addEventListener('submit', function(e) {
      e.preventDefault();
      if (input.value) {
        socket.emit('chat message', input.value);
        input.value = '';
      }
    });

    socket.on('chat message', function(msg) {
      const item = document.createElement('li');
      item.textContent = msg;
      messages.appendChild(item);
      window.scrollTo(0, document.body.scrollHeight);
    });
  </script>
</body>
</html>
