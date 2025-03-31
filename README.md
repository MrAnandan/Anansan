<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anandan S - Professional Profile</title>
    <style>
        :root {
            --primary-color: #3498db;
            --secondary-color: #2ecc71;
            --dark-color: #2c3e50;
            --light-color: #f9f9f9;
            --text-color: #333;
            --muted-color: #7f8c8d;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--light-color);
            padding: 20px;
        }
        
        .profile-header {
            text-align: center;
            margin-bottom: 40px;
            padding-bottom: 20px;
            border-bottom: 2px solid var(--primary-color);
        }
        
        .profile-name {
            color: var(--dark-color);
            margin-bottom: 5px;
            font-size: 2.2em;
        }
        
        .contact-info {
            color: var(--muted-color);
            margin-bottom: 15px;
        }
        
        .section-title {
            color: var(--dark-color);
            border-bottom: 2px solid var(--primary-color);
            padding-bottom: 5px;
            margin-top: 30px;
            margin-bottom: 20px;
        }
        
        .timeline-container {
            max-width: 1000px;
            margin: 0 auto;
        }
        
        .timeline {
            position: relative;
            padding-left: 250px;
        }
        
        .timeline::before {
            content: '';
            position: absolute;
            left: 220px;
            top: 0;
            bottom: 0;
            width: 4px;
            background: linear-gradient(to bottom, var(--primary-color), var(--secondary-color));
            border-radius: 2px;
        }
        
        .timeline-item {
            position: relative;
            margin-bottom: 40px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            padding: 20px;
            transition: transform 0.3s ease;
            display: flex;
            align-items: center;
            min-height: 150px;
        }
        
        .timeline-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }
        
        .timeline-item::before {
            content: '';
            position: absolute;
            left: 200px;
            top: 50%;
            transform: translateY(-50%);
            width: 20px;
            height: 20px;
            border-radius: 50%;
            background: var(--secondary-color);
            border: 4px solid var(--primary-color);
            z-index: 2;
        }
        
        .timeline-image {
            position: absolute;
            left: -230px;
            width: 180px;
            height: 180px;
            border-radius: 8px;
            object-fit: cover;
            border: 4px solid var(--primary-color);
            box-shadow: 0 3px 10px rgba(0,0,0,0.2);
        }
        
        .timeline-content {
            flex: 1;
        }
        
        .timeline-date {
            color: var(--muted-color);
            font-weight: bold;
            margin-bottom: 5px;
        }
        
        .timeline-position {
            color: var(--dark-color);
            font-size: 1.4em;
            margin-bottom: 5px;
        }
        
        .timeline-company {
            color: var(--primary-color);
            font-weight: bold;
            margin-bottom: 10px;
        }
        
        .timeline-description {
            color: #555;
        }
        
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            margin-bottom: 30px;
        }
        
        .skills-column {
            flex: 1;
            min-width: 250px;
        }
        
        .skills-list {
            list-style-type: none;
            padding: 0;
        }
        
        .skills-list li {
            background: #e0f7fa;
            color: #00838f;
            padding: 8px 15px;
            border-radius: 20px;
            margin-bottom: 8px;
            display: inline-block;
            margin-right: 8px;
        }
        
        .two-column {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        
        .column {
            flex: 1;
            min-width: 300px;
        }
        
        @media (max-width: 900px) {
            .timeline {
                padding-left: 30px;
            }
            
            .timeline::before {
                left: 10px;
            }
            
            .timeline-item {
                flex-direction: column;
                padding-top: 180px;
                position: relative;
            }
            
            .timeline-item::before {
                left: -5px;
                top: 90px;
                transform: none;
            }
            
            .timeline-image {
                position: absolute;
                left: 50%;
                transform: translateX(-50%);
                top: 20px;
                width: 120px;
                height: 120px;
            }
        }
    </style>
</head>
<body>
    <div class="profile-header">
        <h1 class="profile-name">Anandan S</h1>
        <div class="contact-info">Email: anandans0007@gmail.com | Mobile: 8072179149</div>
    </div>

    <div class="timeline-container">
        <h2 class="section-title">Education</h2>
        
        <div class="timeline">
            <!-- MBA -->
            <div class="timeline-item">
                <img src="https://images.unsplash.com/photo-1523050854058-8df90110c9f1?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="MBA" class="timeline-image">
                <div class="timeline-content">
                    <div class="timeline-date">Sep 2021 – Aug 2023</div>
                    <h2 class="timeline-position">MBA in Human Resources & Finance</h2>
                    <p class="timeline-description">CGPA: 7.5/10</p>
                </div>
            </div>
            
            <!-- BE -->
            <div class="timeline-item">
                <img src="https://images.unsplash.com/photo-1523240795612-9a054b0db644?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="BE" class="timeline-image">
                <div class="timeline-content">
                    <div class="timeline-date">Aug 2017 – Jul 2021</div>
                    <h2 class="timeline-position">BE in Mechanical Engineering</h2>
                    <p class="timeline-description">CGPA: 7.7/10</p>
                </div>
            </div>
        </div>

        <h2 class="section-title">Technical Skills</h2>
        <div class="skills-container">
            <div class="skills-column">
                <h3>Tools</h3>
                <ul class="skills-list">
                    <li>SAP</li>
                    <li>ZOHO ERP</li>
                    <li>SQL</li>
                    <li>TABLEAU</li>
                    <li>POWER BI</li>
                </ul>
            </div>
            <div class="skills-column">
                <h3>Data Analytics</h3>
                <ul class="skills-list">
                    <li>MS Excel</li>
                    <li>Power BI</li>
                    <li>Google Sheets</li>
                </ul>
            </div>
            <div class="skills-column">
                <h3>Collaboration Tools</h3>
                <ul class="skills-list">
                    <li>MS PowerPoint</li>
                    <li>MS Word</li>
                    <li>Google Docs</li>
                    <li>Outlook</li>
                </ul>
            </div>
        </div>

        <h2 class="section-title">Soft Skills</h2>
        <div class="skills-container">
            <div class="skills-column">
                <ul class="skills-list">
                    <li>Excellent Communication</li>
                    <li>Problem Solving</li>
                    <li>Strategic Thinking</li>
                    <li>Team Collaboration</li>
                </ul>
            </div>
            <div class="skills-column">
                <ul class="skills-list">
                    <li>Time Management</li>
                    <li>Adaptability</li>
                    <li>Stakeholder Management</li>
                    <li>Leadership</li>
                </ul>
            </div>
            <div class="skills-column">
                <ul class="skills-list">
                    <li>Strong Analytical Skills</li>
                    <li>Client-Oriented</li>
                    <li>Multi-tasking</li>
                    <li>Discretion</li>
                </ul>
            </div>
            <div class="skills-column">
                <ul class="skills-list">
                    <li>Responsive</li>
                    <li>Collaborative</li>
                    <li>Resourceful</li>
                    <li>Dedicated</li>
                </ul>
            </div>
        </div>

        <h2 class="section-title">Professional Experience</h2>
        <div class="timeline">
            <!-- HR Metro Composite -->
            <div class="timeline-item">
                <img src="https://images.unsplash.com/photo-1552664730-d307ca884978?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="HR Metro Composite" class="timeline-image">
                <div class="timeline-content">
                    <div class="timeline-date">Jul 2023 – Oct 2024</div>
                    <h2 class="timeline-position">HR Professional</h2>
                    <div class="timeline-company">HR Metro Composite</div>
                    <ul class="timeline-description">
                        <li>Managed onboarding and offboarding processes, including orientation, documentation, and exit interviews</li>
                        <li>Maintained accurate employee data in HR systems ensuring compliance with data privacy regulations</li>
                        <li>Provided guidance on HR policies and resolved queries from candidates and employees</li>
                        <li>Ensured adherence to HR policies and regulations, identifying and escalating policy breaches</li>
                        <li>Prepared HR reports and conducted data analysis to support decision-making</li>
                        <li>Conducted end-to-end recruitment activities including sourcing, interviewing, and onboarding</li>
                    </ul>
                </div>
            </div>
            
            <!-- Internships -->
            <div class="two-column">
                <div class="column">
                    <div class="timeline-item">
                        <img src="https://images.unsplash.com/photo-1521791136064-7986c2920216?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Life Style Housing" class="timeline-image">
                        <div class="timeline-content">
                            <div class="timeline-date">Aug 2022 – Sep 2022</div>
                            <h2 class="timeline-position">HR Intern</h2>
                            <div class="timeline-company">Life Style Housing And Infrastructure</div>
                            <ul class="timeline-description">
                                <li>Assisted in talent acquisition by screening resumes and scheduling interviews</li>
                                <li>Supported HR teams in coordinating company events</li>
                                <li>Helped implement employee engagement initiatives</li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="column">
                    <div class="timeline-item">
                        <img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Ithano Pure Tech" class="timeline-image">
                        <div class="timeline-content">
                            <div class="timeline-date">Jan 2023 – Mar 2023</div>
                            <h2 class="timeline-position">HR Intern</h2>
                            <div class="timeline-company">Ithano Pure Tech</div>
                            <ul class="timeline-description">
                                <li>Assisted in maintaining employee records</li>
                                <li>Supported recruitment processes</li>
                                <li>Helped with HR documentation</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <h2 class="section-title">Projects</h2>
        <div class="two-column">
            <div class="column">
                <div class="timeline-item">
                    <img src="https://images.unsplash.com/photo-1450101499163-c8848c66ca85?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="HR Policies" class="timeline-image">
                    <div class="timeline-content">
                        <div class="timeline-date">Jan 2023 – Mar 2023</div>
                        <h2 class="timeline-position">HR Policies and Implementation</h2>
                        <ul class="timeline-description">
                            <li>Developed and implemented HR policies to align with organizational objectives</li>
                            <li>Improved employee relations through policy standardization</li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="column">
                <div class="timeline-item">
                    <img src="https://images.unsplash.com/photo-1522071820081-009f0129c71c?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Employee Engagement" class="timeline-image">
                    <div class="timeline-content">
                        <div class="timeline-date">Aug 2022 – Sep 2022</div>
                        <h2 class="timeline-position">Employee Engagement</h2>
                        <ul class="timeline-description">
                            <li>Designed initiatives to enhance employee commitment</li>
                            <li>Resulted in improved organizational performance</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>

        <h2 class="section-title">Languages</h2>
        <div class="skills-container">
            <div class="skills-column">
                <ul class="skills-list">
                    <li>English: Professional Proficiency</li>
                    <li>Tamil: Native Proficiency</li>
                </ul>
            </div>
        </div>
    </div>
</body>
</html>
