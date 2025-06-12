<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nithyashree N | Cloud Engineer & AI/ML Enthusiast</title>
  <style>
    :root {
      --bg-light: #f4f6f8;
      --text-light: #222;
      --bg-dark: #1e293b;
      --text-dark: #f1f5f9;
    }

    body {
      font-family: 'Inter', sans-serif;
      background-color: var(--bg-light);
      color: var(--text-light);
      transition: background 0.3s, color 0.3s;
      line-height: 1.6;
    }

    body.dark {
      background-color: var(--bg-dark);
      color: var(--text-dark);
    }

    header {
      background: #1f2937;
      color: white;
      padding: 2rem;
      text-align: center;
      position: relative;
    }

    header h1 { font-size: 2.5rem; }
    header p { font-size: 1.2rem; margin-top: 0.5rem; }

    .toggle-btn {
      position: absolute;
      top: 1.5rem;
      right: 1.5rem;
      background: #fff;
      border: none;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      cursor: pointer;
      font-weight: bold;
    }

    body.dark .toggle-btn {
      background: #475569;
      color: white;
    }

    .container {
      max-width: 900px;
      margin: auto;
      padding: 2rem;
    }

    h2 {
      color: #1f2937;
      border-bottom: 2px solid #ddd;
      padding-bottom: 0.5rem;
      margin-bottom: 1rem;
    }

    body.dark h2 {
      color: #f1f5f9;
      border-color: #555;
    }

    ul { list-style-type: none; padding-left: 1.5rem; }
    ul li::before {
      content: "\2192  "; /* Right arrow */
      color: #2563eb;
      font-weight: bold;
    }

    section { margin-bottom: 2rem; }

    footer {
      text-align: center;
      padding: 1rem;
      background: #e5e7eb;
      font-size: 0.9rem;
    }

    body.dark footer {
      background: #334155;
    }

    a { color: #2563eb; text-decoration: none; }
    a:hover { text-decoration: underline; }

    .bar-container {
      background: #e5e7eb;
      border-radius: 5px;
      margin: 0.5rem 0;
      overflow: hidden;
    }

    .bar {
      height: 20px;
      background: #2563eb;
      text-align: right;
      padding-right: 0.5rem;
      color: white;
      font-size: 0.8rem;
      line-height: 20px;
    }

    .resume-button {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.6rem 1.2rem;
      background: #2563eb;
      color: white;
      border-radius: 8px;
      font-weight: bold;
      text-decoration: none;
    }

    .resume-button:hover {
      background: #1e40af;
    }
  </style>
</head>
<body>
  <header>
    <h1>Nithyashree N</h1>
    <p>Cloud Engineer Intern @ Titan | IEEE Author | AI/ML Enthusiast | ISRO Aspirant</p>
    <button class="toggle-btn" onclick="toggleMode()">Toggle Mode</button>
  </header>

  <div class="container">
    <section>
      <p>I am a highly motivated and detail-oriented cloud engineer with a strong passion for leveraging AWS and AI technologies to solve real-world problems. With a foundation in machine learning and cloud architecture, I build secure and scalable solutions that drive performance and impact.</p>
    </section>

    <section>
      <h2>Skills</h2>
      <ul>
        <li>AWS (Lambda, EC2, S3, SNS, SES, CloudWatch, Cost Explorer, QuickSight)</li>
        <li>Python, SQL, Bash, JavaScript</li>
        <li>AI/ML: PyTorch, OpenCV, ResNet, Swin Transformer, ConvNeXt</li>
        <li>DevOps Tools: Git, GitHub Actions, Grafana, Timestream, IAM</li>
        <li>Cloud Architecture, Cost Optimization, FinOps Principles</li>
      </ul>
    </section>

    <section>
      <h2>Projects</h2>
      <ul>
        <li><strong>AI-Powered Issue Resolution Bot</strong> – Integrated AWS Q with Atlassian Confluence to resolve customer issues efficiently.</li>
        <li><strong>Multi-Channel Alert System</strong> – Real-time CPU alerts across AWS Infra using Lambda, SNS & CloudWatch.</li>
        <li><strong>Real-Time PageSpeed Analytics</strong> – AWS Lambda, DynamoDB, and Grafana for 9+ major retail brands.</li>
        <li><strong>Cost Saving Distribution Engine</strong> – Automated AWS Cost Hub suggestions sent via SES & Outlook daily.</li>
        <li><strong>Image & Video Deduplication System</strong> – SHA-1024, ResNet, ConvNeXt, Swin Transformer on Azure for optimized cloud storage.</li>
      </ul>
    </section>

    <section>
      <h2>Research & Publication</h2>
      <p><strong>IEEE Publication</strong>: "Image Deduplication in Cloud Storage using SHA-1024 & Perceptual Algorithm"<br />
      Published in IEEE Conference Proceedings, 2024.<br />
      <em><a href="https://ieeexplore.ieee.org/document/10860091" target="_blank">View Paper on IEEE Xplore</a></em></p>
    </section>

    <section>
      <h2>Experience</h2>
      <p><strong>Cloud Engineer Intern @ Titan Company Ltd.</strong> (Oct 2024 – Present)</p>
      <ul>
        <li>Developed automated monitoring systems using AWS CloudWatch Synthetics for real-time health checks.</li>
        <li>Built scalable serverless solutions using Lambda, SES, and Cost Explorer to enhance cloud cost efficiency.</li>
        <li>Designed interactive dashboards in AWS QuickSight and Grafana for data-driven insights and reporting.</li>
        <li>Worked with Timestream DB to store and query time-series data for website performance analytics.</li>
      </ul>
    </section>

    <section>
      <h2>Certifications</h2>
      <p><strong>AWS Certified Solutions Architect – Associate</strong><br />
      Aggregate: 880/1000<br />
      Key Skills: AWS | Cloud Computing | Cloud Services<br />
      <br />
      This certification validates expertise in designing and deploying scalable AWS cloud solutions. It demonstrates proficiency in architecting and implementing secure, reliable, and cost-effective cloud applications on the AWS platform. Certified in creating, managing, and designing internal cloud applications, migrating operations to the cloud, and minimizing data loss and downtime.</p>
    </section>

    <section>
      <h2>Languages Known</h2>
      <p>English – Read, Write, Speak</p>
      <div class="bar-container"><div class="bar" style="width: 100%">100%</div></div>
      <p>French – Read, Write</p>
      <div class="bar-container"><div class="bar" style="width: 70%">70%</div></div>
      <p>Tamil – Native</p>
      <div class="bar-container"><div class="bar" style="width: 95%">95%</div></div>
      <p>Hindi – Understand Only</p>
      <div class="bar-container"><div class="bar" style="width: 40%">40%</div></div>
    </section>

    <section>
      <h2>Contact</h2>
      <p>Email: <a href="mailto:nithyashreenamasivayam@gmail.com">nithyashreenamasivayam@gmail.com</a></p>
      <p>GitHub: <a href="https://github.com/nithyashree-n27" target="_blank">github.com/nithyashree-n27</a></p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/nithyashree-n-06a166358" target="_blank">linkedin.com/in/nithyashree-n-06a166358</a></p>
      <a class="resume-button" href="resume.pdf" download>Download Resume</a>
    </section>
  </div>

  <footer>
    © 2025 Nithyashree N.
  </footer>

  <script>
    function toggleMode() {
      document.body.classList.toggle("dark");
    }
  </script>
</body>
</html>
