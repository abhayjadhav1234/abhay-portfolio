<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Abhay Jadhav | Portfolio</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: "Segoe UI", Arial, sans-serif;
}

body {
  background: #0b0f19;
  color: #ffffff;
  line-height: 1.6;
  scroll-behavior: smooth;
}

a {
  color: #38bdf8;
  text-decoration: none;
  transition: 0.3s;
}

a:hover { color: #0ea5e9; }

header {
  background: linear-gradient(135deg, #0a2540, #111827);
  text-align: center;
  padding: 120px 20px 80px;
  display: flex;
  flex-direction: column;
  align-items: center;
  animation: fadeIn 1.5s ease;
}

header img {
  width: 160px;
  height: 160px;
  border-radius: 50%;
  object-fit: cover;
  border: 4px solid #38bdf8;
  margin-bottom: 20px;
  animation: fadeIn 1.5s ease;
}

header h1 {
  font-size: 56px;
  margin-bottom: 10px;
  animation: slideDown 1s ease;
  text-align: center;
}

.title-container { display: flex; justify-content: center; width: 100%; }

.title {
  font-size: 24px;
  color: #38bdf8;
  font-weight: 500;
  letter-spacing: 0.5px;
  animation: fadeIn 2s ease;
  text-align: center;
}

.lang-switch {
  margin-top: 20px;
}

.lang-btn {
  background: #1f2933;
  border: 1px solid #38bdf8;
  color: #38bdf8;
  padding: 7px 14px;
  border-radius: 6px;
  margin: 0 5px;
  cursor: pointer;
  transition: 0.3s;
  font-size: 14px;
}

.lang-btn:hover {
  background: #38bdf8;
  color: #020617;
}

section {
  padding: 70px 12%;
  opacity: 0;
  transform: translateY(40px);
  transition: all 0.8s ease;
}

section.visible {
  opacity: 1;
  transform: translateY(0);
}

h2 {
  font-size: 36px;
  margin-bottom: 25px;
  color: #38bdf8;
}

p {
  color: #d1d5db;
  font-size: 17px;
  max-width: 900px;
}

.skills span {
  display: inline-block;
  background: #1f2933;
  padding: 9px 16px;
  margin: 6px;
  border-radius: 20px;
  font-size: 14px;
  border: 1px solid #374151;
  transition: 0.3s;
}

.skills span:hover {
  background: #38bdf8;
  color: #020617;
  transform: scale(1.05);
}

.card {
  background: #111827;
  padding: 24px;
  border-radius: 14px;
  margin: 18px 0;
  border: 1px solid #1f2933;
  transition: 0.4s;
  box-shadow: 0 0 20px rgba(0,0,0,0.2);
}

.card:hover {
  transform: translateY(-8px) scale(1.02);
  border-color: #38bdf8;
  box-shadow: 0 15px 40px rgba(56,189,248,0.3);
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 22px;
  margin-top: 20px;
}

footer {
  text-align: center;
  padding: 28px;
  background: #020617;
  color: #9ca3af;
  font-size: 14px;
}

.btn {
  display: inline-block;
  margin-top: 25px;
  padding: 13px 26px;
  background: #38bdf8;
  color: #020617;
  border-radius: 8px;
  font-weight: bold;
  transition: 0.3s;
}

.btn:hover {
  background: #0ea5e9;
  transform: scale(1.05);
}

.doc-btn {
  display: inline-block;
  margin: 10px 10px 0 0;
  padding: 11px 20px;
  background: #1f2937;
  border: 1px solid #38bdf8;
  border-radius: 8px;
  color: #38bdf8;
  transition: 0.3s;
  font-size: 15px;
}

.doc-btn:hover {
  background: #38bdf8;
  color: #020617;
  transform: translateY(-4px);
}

@media (max-width: 768px) {
  section { padding: 50px 7%; }
  header h1 { font-size: 38px; }
}

@keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }
@keyframes slideDown { from { opacity: 0; transform: translateY(-30px); } to { opacity: 1; transform: translateY(0); } }

</style>
</head>
<body>

<header>
  <img src="profile.jpg" alt="Abhay Jadhav Profile Picture">
  <h1>Abhay Balasaheb Jadhav</h1>
  <div class="title-container">
    <p class="title" id="title">Autonomous Driving & Robotics Engineer</p>
  </div>

  <div class="lang-switch">
    <button class="lang-btn" onclick="switchLang('en')">English</button>
    <button class="lang-btn" onclick="switchLang('de')">Deutsch</button>
  </div>

  <a class="btn" href="#contact" id="contactBtn">Contact Me</a>
</header>

<section id="about">
  <h2 data-en="About Me" data-de="Über Mich">About Me</h2>
  <p data-en="I am a Master’s graduate in Commercial Vehicle Technology from RPTU Kaiserslautern-Landau with expertise in radar-based localisation, SLAM, robotics, and automotive software engineering. I completed my Master’s degree in 2026 with a final grade of 1.6. I have hands-on experience working with autonomous driving systems at CARIAD SE, SICK AG, and Bosch Chassis Systems."
     data-de="Ich habe meinen Master in Nutzfahrzeugtechnik an der RPTU Kaiserslautern-Landau abgeschlossen, spezialisiert auf radarbasierte Lokalisierung, SLAM, Robotik und Automotive-Softwareentwicklung. Ich habe meinen Master 2026 mit der Endnote 1,6 abgeschlossen und praktische Erfahrung mit autonomen Fahrsystemen bei CARIAD SE, SICK AG und Bosch Chassis Systems gesammelt.">I am a Master’s graduate in Commercial Vehicle Technology from RPTU Kaiserslautern-Landau with expertise in radar-based localisation, SLAM, robotics, and automotive software engineering. I completed my Master’s degree in 2026 with a final grade of 1.6. I have hands-on experience working with autonomous driving systems at CARIAD SE, SICK AG, and Bosch Chassis Systems.</p>
</section>

<section id="skills">
  <h2 data-en="Skills" data-de="Fähigkeiten">Skills</h2>
  <div class="skills">
    <span>C++</span>
    <span>Python</span>
    <span>ROS</span>
    <span>ROS2</span>
    <span>SLAM</span>
    <span>Radar Localisation</span>
    <span>Autonomous Driving</span>
    <span>ADAS</span>
    <span>CarMaker</span>
    <span>MATLAB / Simulink</span>
    <span>PyTorch</span>
    <span>Automotive Systems</span>
  </div>
</section>

<section id="experience">
  <h2 data-en="Experience" data-de="Erfahrung">Experience</h2>

  <div class="card" data-en="CARIAD SE (Volkswagen Group) – Master’s Thesis & Internship: Radar-based vehicle localisation and SLAM for autonomous driving under degraded GNSS conditions."
       data-de="CARIAD SE (Volkswagen Group) – Masterarbeit & Praktikum: Radarbasierte Fahrzeuglokalisierung und SLAM für autonomes Fahren unter verschlechterten GNSS-Bedingungen.">CARIAD SE (Volkswagen Group) – Master’s Thesis & Internship: Radar-based vehicle localisation and SLAM for autonomous driving under degraded GNSS conditions.</div>

  <div class="card" data-en="SICK AG – Robotics Internship: Development of localisation software using C++ and ROS2, system testing and validation."
       data-de="SICK AG – Robotik Praktikum: Entwicklung von Lokalisierungssoftware mit C++ und ROS2, Systemtests und Validierung.">SICK AG – Robotics Internship: Development of localisation software using C++ and ROS2, system testing and validation.</div>

  <div class="card" data-en="Bosch Chassis Systems India – Graduate Apprentice: Design and testing of brake system components and development of automation tools using VBA."
       data-de="Bosch Chassis Systems India – Graduate Apprentice: Entwurf und Test von Bremssystemkomponenten und Entwicklung von Automatisierungstools mit VBA.">Bosch Chassis Systems India – Graduate Apprentice: Design and testing of brake system components and development of automation tools using VBA.</div>
</section>

<section id="docs">
  <h2 data-en="Documents & Employment References" data-de="Dokumente & Arbeitszeugnisse">Documents & Employment References</h2>
  <p data-en="You can view or download my academic and professional documents below:"
     data-de="Sie können meine akademischen und beruflichen Dokumente unten ansehen oder herunterladen:">You can view or download my academic and professional documents below:</p>

  <a class="doc-btn" href="https://drive.google.com/file/d/1H3qs15LcOnExYhRQBm_yeZXoltDdvcKI/view?usp=drivesdk" target="_blank" data-en="CV" data-de="Lebenslauf">🏢 CV</a>
  <a class="doc-btn" href="https://drive.google.com/file/d/1gM33zuszWJHtlXDhFQVmNM_5Ufko5Ys2/view?usp=drivesdk" target="_blank" data-en="Master’s Transcript" data-de="Master Transcript">🎓 Master’s Transcript</a>
  <a class="doc-btn" href="https://drive.google.com/file/d/1-FpLX9457taQ63g-Wf1lIUUwtGAb471N/view?usp=drivesdk" target="_blank" data-en="Bachelor’s Transcript" data-de="Bachelor Transcript">📄 Bachelor’s Transcript</a>
  <a class="doc-btn" href="https://drive.google.com/file/d/1CkyjdwLysbhrBgIPrNs23szEwdCayssB/view?usp=drivesdk" target="_blank" data-en="Bachelor’s Degree" data-de="Bachelorabschluss">🎓 Bachelor’s Degree</a>
  <a class="doc-btn" href="https://drive.google.com/file/d/1XCLIQLBlnM8FzwH9EIlS1a1nPLWfNXTt/view?usp=drivesdk" target="_blank" data-en="Recommendation Letter" data-de="Empfehlungsschreiben">✉️ Recommendation Letter</a>
  <a class="doc-btn" href="https://drive.google.com/file/d/14bmo8HbqxNC22Y7tHkD6ZiC0Qo0cpE1g/view?usp=drivesdk" target="_blank" data-en="Seminar Electromobility Certificate" data-de="Seminar Elektromobilität Zertifikat">📜 Seminar Electromobility Certificate</a>

  <h3 style="margin-top: 25px; color:#38bdf8;" data-en="Employment References" data-de="Arbeitszeugnisse">Employment References</h3>
  <a class="doc-btn" href="https://drive.google.com/file/d/1w-AFurYIn-h00TM6fzIYe3cOgJFBduVb/view" target="_blank" data-en="Employment Reference 1" data-de="Arbeitszeugnis 1">🏢 Employment Reference 1</a>
  <a class="doc-btn" href="https://drive.google.com/file/d/1IGKlR3h-FCsLRfGxHnl6Yd-t9DoClTd4/view" target="_blank" data-en="Employment Reference 2" data-de="Arbeitszeugnis 2">🏢 Employment Reference 2</a>
  <a class="doc-btn" href="https://drive.google.com/file/d/1ptd1wY4Jq1ewx-d61IePjbci7B64oWdr/view" target="_blank" data-en="Employment Reference 3" data-de="Arbeitszeugnis 3">🏢 Employment Reference 3</a>
</section>

<section id="contact">
  <h2 data-en="Contact" data-de="Kontakt">Contact</h2>
  <p data-en="Email: " data-de="E-Mail: ">Email: <a href="mailto:Jadhav.abhay426@gmail.com">Jadhav.abhay426@gmail.com</a></p>
  <p data-en="Phone: " data-de="Telefon: ">Phone: <a href="tel:+4917687976607">+49 176 87976607</a></p>
  <p data-en="LinkedIn: " data-de="LinkedIn: ">LinkedIn: <a href="https://www.linkedin.com/in/abhay-balasaheb-jadhav-72a0a5127/" target="_blank">linkedin.com/in/abhay-balasaheb-jadhav</a></p>
</section>

<footer>
  © 2026 Abhay Balasaheb Jadhav | Automotive & Autonomous Systems Portfolio
</footer>

<script>
const sections = document.querySelectorAll("section");
const observer = new IntersectionObserver(entries => {
  entries.forEach(entry => { if(entry.isIntersecting){ entry.target.classList.add("visible"); } });
},{threshold:0.15});
sections.forEach(sec => observer.observe(sec));

function switchLang(lang){
  document.querySelectorAll("[data-en]").forEach(el=>{
    if(el.tagName.toLowerCase()==='p' && el.innerHTML.includes('<a')){
      const enText=el.getAttribute('data-en');
      const deText=el.getAttribute('data-de');
      const parts=el.innerHTML.split(/<a/);
      el.innerHTML=((lang==='de')?deText:enText)+"<a"+parts[1];
    } else {
      el.textContent=(lang==='de')?el.getAttribute('data-de'):el.getAttribute('data-en');
    }
  });
  document.getElementById('title').textContent=(lang==='de')?"Autonomes Fahren & Robotik Ingenieur":"Autonomous Driving & Robotics Engineer";
  document.getElementById('contactBtn').textContent=(lang==='de')?"Kontakt":"Contact Me";
} 
</script>

</body>
</html>
