<section style="
  max-width: 1000px;
  margin: 3rem auto;
  padding: 3rem;
  border-radius: 25px;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
  color: #e0e0e0;
  perspective: 1200px;
  overflow: hidden;
">

  <!-- Nombre y presentación -->
  <div style="text-align:center; margin-bottom: 3rem; transform-style: preserve-3d;">
    <h1 style="
      font-size: 3rem;
      background: linear-gradient(90deg, #6a11cb, #2575fc);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      letter-spacing: 1px;
      text-shadow: 0 5px 15px rgba(0,0,0,0.6);
      transform: translateZ(50px) rotateX(5deg);
      transition: transform 0.5s;
    ">Gisele Ortiz</h1>
    <p style="
      font-size: 1.2rem; 
      max-width: 700px; 
      margin:auto; 
      line-height:1.6; 
      color:#cfd8dc;
      transform: translateZ(30px);
    ">
      Apasionada por el desarrollo web y la gestión ágil. Combino creatividad y técnica para construir soluciones escalables y eficientes.
    </p>
  </div>

  <!-- Habilidades en tarjetas 3D -->
  <div style="margin-bottom: 3rem; display: flex; flex-wrap: wrap; gap: 1rem; justify-content: center; perspective: 800px;">
    <div style="
      background: linear-gradient(145deg, #1f2937, #2e3b4e);
      border-radius: 15px;
      padding: 1rem 2rem;
      font-weight: 600;
      color: #fff;
      box-shadow: 0 10px 25px rgba(0,0,0,0.6);
      transform: rotateY(-10deg) rotateX(5deg);
      transition: transform 0.5s, box-shadow 0.5s;
      cursor: pointer;
    " onmouseover="this.style.transform='rotateY(0deg) rotateX(0deg) scale(1.1)'; this.style.boxShadow='0 20px 40px rgba(0,0,0,0.8)';" onmouseout="this.style.transform='rotateY(-10deg) rotateX(5deg) scale(1)'; this.style.boxShadow='0 10px 25px rgba(0,0,0,0.6)';">
      JavaScript
    </div>
    <div style="
      background: linear-gradient(145deg, #1f2937, #2e3b4e);
      border-radius: 15px;
      padding: 1rem 2rem;
      font-weight: 600;
      color: #fff;
      box-shadow: 0 10px 25px rgba(0,0,0,0.6);
      transform: rotateY(10deg) rotateX(-5deg);
      transition: transform 0.5s, box-shadow 0.5s;
      cursor: pointer;
    " onmouseover="this.style.transform='rotateY(0deg) rotateX(0deg) scale(1.1)'; this.style.boxShadow='0 20px 40px rgba(0,0,0,0.8)';" onmouseout="this.style.transform='rotateY(10deg) rotateX(-5deg) scale(1)'; this.style.boxShadow='0 10px 25px rgba(0,0,0,0.6)';">
      React
    </div>
    <div style="
      background: linear-gradient(145deg, #1f2937, #2e3b4e);
      border-radius: 15px;
      padding: 1rem 2rem;
      font-weight: 600;
      color: #fff;
      box-shadow: 0 10px 25px rgba(0,0,0,0.6);
      transform: rotateY(-5deg) rotateX(5deg);
      transition: transform 0.5s, box-shadow 0.5s;
      cursor: pointer;
    " onmouseover="this.style.transform='rotateY(0deg) rotateX(0deg) scale(1.1)'; this.style.boxShadow='0 20px 40px rgba(0,0,0,0.8)';" onmouseout="this.style.transform='rotateY(-5deg) rotateX(5deg) scale(1)'; this.style.boxShadow='0 10px 25px rgba(0,0,0,0.6)';">
      HTML & CSS
    </div>
    <div style="
      background: linear-gradient(145deg, #1f2937, #2e3b4e);
      border-radius: 15px;
      padding: 1rem 2rem;
      font-weight: 600;
      color: #fff;
      box-shadow: 0 10px 25px rgba(0,0,0,0.6);
      transform: rotateY(5deg) rotateX(-5deg);
      transition: transform 0.5s, box-shadow 0.5s;
      cursor: pointer;
    " onmouseover="this.style.transform='rotateY(0deg) rotateX(0deg) scale(1.1)'; this.style.boxShadow='0 20px 40px rgba(0,0,0,0.8)';" onmouseout="this.style.transform='rotateY(5deg) rotateX(-5deg) scale(1)'; this.style.boxShadow='0 10px 25px rgba(0,0,0,0.6)';">
      SQL & Sequelize
    </div>
    <div style="
      background: linear-gradient(145deg, #1f2937, #2e3b4e);
      border-radius: 15px;
      padding: 1rem 2rem;
      font-weight: 600;
      color: #fff;
      box-shadow: 0 10px 25px rgba(0,0,0,0.6);
      transform: rotateY(-10deg) rotateX(0deg);
      transition: transform 0.5s, box-shadow 0.5s;
      cursor: pointer;
    " onmouseover="this.style.transform='rotateY(0deg) rotateX(0deg) scale(1.1)'; this.style.boxShadow='0 20px 40px rgba(0,0,0,0.8)';" onmouseout="this.style.transform='rotateY(-10deg) rotateX(0deg) scale(1)'; this.style.boxShadow='0 10px 25px rgba(0,0,0,0.6)';">
      Agile & Kanban
    </div>
  </div>

  <!-- GitHub Stats en 3D -->
  <div style="text-align:center; transform-style: preserve-3d;">
    <h2 style="font-size:1.8rem; color:#6a11cb; margin-bottom:1rem;">Actividad en GitHub</h2>
    <div style="display:inline-block; transform: rotateX(10deg) rotateY(-10deg); transition: transform 0.5s;">
      <img src="https://streak-stats.demolab.com?user=giseleortiz&theme=dark&hide_border=true&background=0f2027,203a43,2c5364" 
           style="border-radius: 25px; max-width:100%; box-shadow: 0 15px 50px rgba(0,0,0,0.7); transition: transform 0.5s;" 
           onmouseover="this.style.transform='translateZ(30px) rotateY(0deg)';" 
           onmouseout="this.style.transform='translateZ(0px) rotateY(-10deg)';"
           alt="GitHub Streak Stats"/>
    </div>
  </div>

</section>        SQL & Sequelize
      </span>
      <span style="background: #1f2937; color: #2575fc; padding: 0.7rem 1.2rem; border-radius: 12px; font-weight: 600; box-shadow: 0 4px 10px rgba(0,0,0,0.5); transition: transform 0.3s; cursor:pointer;">
        Agile & Kanban
      </span>
    </div>
  </div>

  <!-- Cursos y Certificaciones -->
  <div style="margin-bottom: 2rem;">
    <h2 style="font-size: 1.8rem; color:#6a11cb; border-bottom: 2px solid #2575fc; display:inline-block; padding-bottom:5px;">Cursos y Certificaciones</h2>
    <ul style="margin-top:1rem; line-height:1.8; color:#cfd8dc; font-weight:500;">
      <li>Fundamentals of Agile Operations – Agile Explorer</li>
      <li>Team Leader – SkillsBuild</li>
      <li>Neurociencias Aplicadas en Psicología Social – UNGS</li>
      <li>Agile y Equipos Distribuidos – SkillsBuild</li>
      <li>Certificación en JavaScript y Desarrollo Web</li>
    </ul>
  </div>

  <!-- GitHub Stats -->
  <div style="text-align:center;">
    <h2 style="font-size:1.8rem; color:#6a11cb; margin-bottom:1rem;">Actividad en GitHub</h2>
    <img src="https://streak-stats.demolab.com?user=giseleortiz&theme=dark&hide_border=true&background=0f2027,203a43,2c5364" 
         style="border-radius: 20px; max-width:100%; box-shadow: 0 6px 20px rgba(0,0,0,0.5);" 
         alt="GitHub Streak Stats"/>
  </div>
</section>
