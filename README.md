
<h1>Hi, I'm Keyon, an <a href="https://linkedin.com/in/keyon-Alexander">IT Professional</a>☺</h1>

<h2> 👨🏽‍💻Information Technology Projects:</h2>

- <b>osTicket (Help Desk Ticketing System)</b>
  - [osTicket: Installation](https://github.com/keyunit101/osticket-prereqs)
  - [osTicket: Post-Installation Configuration](https://github.com/keyunit101/post-install-config)
  - [osTicket: Ticket Lifecycle Examples](https://github.com/keyunit101/ticket-lifecycle)
- <b>Microsoft Azure</b>
  - [Configuring Active Directory within Azure VMs](https://github.com/keyunit101/configure-ad)
  - [Network Security Groups (NSGs) and Inspecting Network Protocols](https://github.com/keyunit101/azure-network-protocols)

<h2>🤳Connect with me:</h2>


[<img align="left" alt="Josh | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]



[linkedin]: https://linkedin.com/in/keyon-Alexander

<script>
  const greeting = document.querySelector('h1');
  const projectHeading = document.querySelector('h2');
  const colors = ['#ff0000', '#00ff00', '#0000ff', '#ffff00', '#ff00ff'];
  let currentIndex = 0;

  function changeStyles() {
    greeting.style.color = colors[currentIndex];
    projectHeading.style.color = colors[currentIndex];
    currentIndex = (currentIndex + 1) % colors.length;
  }

  setInterval(changeStyles, 1000);
</script>
