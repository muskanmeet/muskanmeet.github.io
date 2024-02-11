<!DOCTYPE html>
<html lang="en" data-theme="dark">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Muskanmeet Kaur - Resume</title>
  <link rel="stylesheet" href="styles.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
  <link href="https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
  <header>
    <img src="pic_muskanmeet.jpg" alt="Muskanmeet Kaur" class="profile-image">
    <h1>MUSKANMEET KAUR</h1>
    <p>muskan99@icloud.com | (647)-917-9353</p>
    <a href="https://www.linkedin.com/in/muskanmeetkaur" target="_blank"><i id="linkedin-icon" class="fab fa-linkedin fa-2x"></i></a>
  </header>

  <div class="container">
    <section id="objective">
      <h2>OBJECTIVE</h2>
      <p>Seeking a full-time opportunity in Project/Product Manager role. Inquisitive, detail-oriented analyst with a strong foundation in math, programming logic, business, and quantitative statistics. Passionate about data science and motivated to drive projects from start to finish as a part of a dynamic team.</p>
    </section>

    <section id="technical-skills">
      <h2>TECHNICAL SKILLS</h2>
      <p>Skills: Requirement Gathering, Data Cleaning, Data Manipulation, Querying data, Predictive Analysis, Trends Analysis, Data Visualization & Reporting, Cloud Computing (AWS Certification – In training).</p>
      <p>Analytical Softwares: SQL Server Management Studio, Power BI, Business Objects, Salesforce, Content Management System, Zendesk.</p>
      <p>Programming Languages: SQL, Java, Python, JavaScript, CSS, and HTML.</p>
      <p>Integrated Development Environment: Visual Studio, IntelliJ, MySQL Workbench, Microsoft SQL Server, and Eclipse.</p>
      <p>Tools: Advanced Excel, JIRA, SharePoint, PowerPoint.</p>
      <p>Soft skills: Team Player, Time Management, Stakeholder Engagement, Leadership, Good Presenter.</p>
    </section>

    <section id="education">
      <h2>EDUCATION</h2>
      <h3>Bachelors in Information Technology with Business minor</h3>
      <p>York University (Present)</p>
      <ul>
        <li>Fourth year student with current GPA – 7.2 / 9.0</li>
        <li>School of Information Technology Scholarship Achiever.</li>
        <li>Provost’s Award Holder.</li>
        <li>Relevant Courses: Object-Oriented Programming, Applied Data Communications and Networks, Using and Designing Database, Systems Engineering/Administration, Machine Learning & Data Mining, Financial and Management Accounting, Web Technologies, Data Structures, Designing User Interfaces, Systems Analysis and Design, Technical Writing.</li>
      </ul>
      <h3>Advanced Diploma in Business Administration</h3>
      <p>George Brown College (August 2017 – August 2020)</p>
      <ul>
        <li>Dean’s Honors List – 3.7 / 4.0</li>
        <li>Relevant Courses: Business Computer Applications, Professional Communications, Management Decision Making, Accounting, Strategic Analysis, Applied Business Planning, Mathematics.</li>
      </ul>
    </section>

    <section id="professional-experience">
      <h2>PROFESSIONAL EXPERIENCE</h2>
      <h3>Product/Project Management Lead (Intern) – IBM Kyndryl</h3>
      <p>September 2023 – Present</p>
      <ul>
        <li>Methodically evaluating reports for software issues, identifying, and categorizing issues with a precision rate of 95%, leading to efficient problem resolution.</li>
        <li>Actively participating in the UAT team, ensuring thorough testing of software / infrastructure functionalities, contributing to a 15% reduction in post-release defects.</li>
        <li>Demonstrating expertise in UAT logging practices, implementing robust mechanisms enhancing system monitoring and troubleshooting capabilities.</li>
        <li>Serving as the Product Owner for an internal tool designed to track and record both internal and external project opportunities for the organization. This strategic role involves overseeing the tool's development, ensuring alignment with organizational goals, and enhancing its functionalities based on user feedback.</li>
        <li>Streamlining the process of consolidating and documenting Software Release Documentation.</li>
        <li>Currently serving as a Scrum Master for RTC Tool, facilitating agile ceremonies, managing sprints, and fostering collaboration among team members.</li>
        <li>Leading and organizing Project Governance meetings to align efforts with project objectives.</li>
        <li>Leveraging SharePoint configuration and other tools to optimize project workflows and productivity.</li>
        <li>Implementing automation through Excel macros to generate and run weekly reports, streamlining data analysis and reporting processes.</li>
        <li>Initiatives to enhance documentation standards, ensuring compliance with industry best practices and fostering a culture of continuous business improvement within the organization.</li>
        <li>Handling ticket management through the ServiceNow platform, ensuring prompt and effective resolution of issues. Collaborating with cross-functional teams to integrate SNOW into the workflow.</li>
      </ul>
    </section>

    <section id="professional-experience">
      <h3>Business Operations Analyst (Intern) – Rakuten Kobo</h3>
      <p>August 2022 – August 2023</p>
      <ul>
        <li>Triaging incoming tickets for Partners area, using Zendesk ticketing system.</li>
        <li>Proposed and successfully implemented system and organizational improvements resulting in approximately 50% less pending tickets workload.</li>
        <li>Setting up automation triggers and building macros for Partners Zendesk Dashboard.</li>
      </ul>
    </section>

    <section id="professional-experience">
      <h3>Services Supervisor – Staples Canada</h3>
      <p>August 2020 – August 2022</p>
      <ul>
        <li>Achieved 95% of the daily sales targets and implemented a new customer service program resulting in a 20% increase in customer satisfaction.</li>
      </ul>
    </section>

    <section id="professional-experience">
      <h3>Print & Marketing Representative – Staples Canada</h3>
      <p>November 2017 – August 2020</p>
      <ul>
        <li>Consistently exceeding the monthly print and marketing sales targets by 10% through effective customer relationship management and solution-focused selling.</li>
      </ul>
    </section>

    <section id="professional-experience">
      <h3>BI Analyst (Intern) – Fortec Solutions, Chandigarh, India</h3>
      <p>December 2016 – August 2017</p>
      <ul>
        <li>Assisting with data integration for operational change and developed dashboards for Seniors &Leaders to administer the data for enhanced operational performance.</li>
      </ul>
    </section>
  </div>

  <footer>
    <p>© 2024 Muskanmeet Kaur</p>
  </footer>

  <div class="theme-switch">
    <label class="switch">
      <input type="checkbox">
      <span class="slider round"></span>
    </label>
  </div>

  <script>
    const themeSwitch = document.querySelector('.theme-switch input[type="checkbox"]');

      function switchTheme(e) {
        if (e.target.checked) {
          document.documentElement.setAttribute('data-theme', 'dark');
          localStorage.setItem('theme', 'dark');
        } else {
          document.documentElement.setAttribute('data-theme', 'light');
          localStorage.setItem('theme', 'light');
        }
      }

      themeSwitch.addEventListener('change', switchTheme, false);

      const currentTheme = localStorage.getItem('theme');
      if (currentTheme) {
        document.documentElement.setAttribute('data-theme', currentTheme);

        if (currentTheme === 'dark') {
          themeSwitch.checked = true;
        }
      }
  </script>
</body>
</html>
