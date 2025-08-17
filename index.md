[📍 Bangalore, India](https://www.google.com/maps/place/SVR+NORTH+EAST+CORNER/data=!4m7!3m6!1s0x3bae6db20ddcfb75:0x838ef57f42134cf4!8m2!3d12.837159!4d77.6890035!16s%2Fg%2F11kq4x659x!19sChIJdfvcDbJtrjsR9EwTQn_1joM?authuser=0&hl=en&rclk=1)
📧 [anupcbalharpure@gmail.com](mailto:anupcbalharpure@gmail.com)
📞 [Call](tel:+919421784577) | 💬 [WhatsApp](https://wa.me/919421784577)
🔗 [LinkedIn](https://www.linkedin.com/in/anupbalharpure)
💻 [Portfolio](https://aatronics.github.io)


---

## 💼 Professional Summary
Software Development Engineer with over 12 years of experience specializing in embedded systems for automotive, IoT, and industrial automation. Expertise in full software development lifecycle (SDLC), C/C++, Python, and delivering robust firmware solutions from concept to deployment.

---

## 🛠️ Technical Skills

- **Programming & Languages**: Embedded C, C, Python, Node.js, LabVIEW, MATLAB  
- **Automotive & Embedded**: AUTOSAR (DCM), Diagnostics (K-line, CAN), Software Download, BLE, FreeRTOS  
- **Protocols & Databases**: SPI, I2C, UART, RS485, MQTT, Websockets, HTTP/HTTPS, PostgreSQL  
- **Platforms & Microcontrollers**: PIC, STM, NXP, Nuvoton, Fujitsu, ESP, Arduino, Raspberry Pi  
- **Tools & Project Management**: Git, JIRA, Rhapsody (Cantata), Eclipse, MPLAB, VS Code, STM32Cube IDE, Lauterbach, Segger J-Link  

---

## 👔 Professional Experience

### **Continental Automotive – Bangalore**  
**Sr. Technical Lead (Software Engineer)**  
*Nov 2022 – Present*  
- Lead embedded software development for Digital Tachographs  
- Delivered major feature sets ahead of schedule with optimized C programming, thorough code reviews, and testing

### **Capgemini Engineering – Bangalore**  
**Professional II (Embedded Engineer)**  
*Aug 2021 – Nov 2022*  
- Developed complex software modules for automotive systems using embedded C  
- Engineered BLE features and ported non-AUTOSAR systems to AUTOSAR-compliant architecture

### **Rewale Engineering Pvt. Ltd. – Pune**  
**Sr. Project Engineer**  
*Apr 2019 – Jul 2021*  
- Led firmware R&D for elevator Automatic Door Controllers  
- Developed motion profile algorithms and RS485-based voice annunciators

### **Radioknit Technologies Pvt. Ltd. – Nagpur**  
**Manager (Tech Support) / Project Coordinator**  
*Apr 2016 – Mar 2019*  
- Managed Embedded, Android, and Java teams  
- Developed Elevator Cloud Gateway (ESP8266) and Node.js microservices for IoT cloud platform

### **Intellect Systems (I) Pvt. Ltd. – Nagpur**  
**Project Engineer**  
*Aug 2015 – Apr 2016*  
- Created firmware for secure wireless elevator interfaces with access control logic

---

## 🎓 Education & Certifications

- **Ph.D. (Electronics)** – RTM Nagpur University, 2016  
- **M.Sc. (Electronics)** – RTM Nagpur University, 2011  
- **Certifications & Achievements**:  
  - Maharashtra State Eligibility Test (SET)  
  - Multiple “Spot” & “Star” Awards at Continental and Capgemini for exceptional delivery  

---

## 📂 Projects
To see a detailed list of my work, including IoT gateways, automotive modules, and firmware algorithms, please visit my projects page.

**[➡️ View My Project Details](./projects.html)**

---
## 👁️ Visitor Counter

![Visitor Counter](https://hitwebcounter.com/counter/counter.php?page=1234567&style=0006&nbdigits=5&type=ip&initCount=0)
---
<!-- Responsive World Map with Interactive Dots -->
<div id="map-container" style="position:relative; display:inline-block; max-width:100%; width:100%; overflow:hidden;">
  <img
    id="world-map"
    src="https://upload.wikimedia.org/wikipedia/commons/9/97/The_Earth_seen_from_Apollo_17.jpg"
    alt="World Map"
    style="width:100%; max-width:600px; border-radius:10px; transition: transform 0.3s;"
    onclick="zoomMap(event)"
  >
  <!-- Blinking dot for Bangalore (relative positioning) -->
  <span
    class="map-dot"
    style="left:70%; top:57%;"
    title="Bangalore, India"
    onclick="showDetails('Bangalore, India\nVisited: 2022-2025\nProjects: Continental Automotive, Capgemini Engineering')"
  ></span>
</div>

<style>
#map-container {
  position: relative;
}
.map-dot {
  position: absolute;
  width: 18px;
  height: 18px;
  background: rgba(255,0,0,0.8);
  border-radius: 50%;
  box-shadow: 0 0 10px 2px #ff0000;
  animation: blink 1s infinite;
  cursor: pointer;
  display: flex;
  align-items: center;
  justify-content: center;
  transform: translate(-50%, -50%);
}
@keyframes blink {
  0%, 100% { opacity: 1; }
  50% { opacity: 0.3; }
}
</style>

<script>
function showDetails(msg) {
  alert(msg);
}

// Simple zoom toggle for desktop/mobile
let zoomed = false;
function zoomMap(e) {
  const img = document.getElementById('world-map');
  zoomed = !zoomed;
  img.style.transform = zoomed ? 'scale(1.7)' : 'scale(1)';
}
</script>