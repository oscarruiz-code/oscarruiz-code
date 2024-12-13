<div align="center">
  <h1>👋 ¡Hola! Soy [oscarruiz-code]</h1>

  <img src="https://media.giphy.com/media/Cmr1OMJ2FN0B2/giphy.gif" width="200"/>

  <p>
    <a href="#" onclick="showLanguage('es')">Español</a> | 
    <a href="#" onclick="showLanguage('en')">English</a>
  </p>
</div>

<div id="content" align="center">
  <!-- Contenido por defecto en Español -->
  <div id="espanol">
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

  <div id="ingles" style="display:none;">
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
  function showLanguage(lang) {
    const espanolDiv = document.getElementById('espanol');
    const inglesDiv = document.getElementById('ingles');

    if (lang === 'es') {
      espanolDiv.style.display = 'block';
      inglesDiv.style.display = 'none';
    } else if (lang === 'en') {
      espanolDiv.style.display = 'none';
      inglesDiv.style.display = 'block';
    }
  }
</script>
