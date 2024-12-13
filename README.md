<div align="center">
  <h1>👋 ¡Hola! Soy [oscarruiz-code]</h1>

  <img src="https://media.giphy.com/media/Cmr1OMJ2FN0B2/giphy.gif" width="200"/>

  <p><a href="#" onclick="setLanguage('en')">English</a> | <a href="#" onclick="setLanguage('es')">Español</a></p>

  <div id="content-es">
    <p>📫 <strong>Conéctate conmigo:</strong></p>
    <p>
      <a href="https://www.linkedin.com/in/%C3%B3scar-ruiz-rosa-78b520245/">
        <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/>
      </a>
    </p>
    <p>📧 <strong>Correo:</strong> <a href="mailto:oscarruizcode@gmail.com">oscarruizcode@gmail.com</a></p>
    <hr/>
    <p>✨ ¡Gracias por visitar mi perfil!</p>
  </div>

  <div id="content-en" style="display:none;">
    <p>📫 <strong>Connect with me:</strong></p>
    <p>
      <a href="https://www.linkedin.com/in/%C3%B3scar-ruiz-rosa-78b520245/">
        <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/>
      </a>
    </p>
    <p>📧 <strong>Email:</strong> <a href="mailto:oscarruizcode@gmail.com">oscarruizcode@gmail.com</a></p>
    <hr/>
    <p>✨ Thanks for visiting my profile!</p>
  </div>
</div>

<script>
  function setLanguage(language) {
    if (language === 'en') {
      document.getElementById('content-es').style.display = 'none';
      document.getElementById('content-en').style.display = 'block';
    } else if (language === 'es') {
      document.getElementById('content-en').style.display = 'none';
      document.getElementById('content-es').style.display = 'block';
    }
  }
</script>
