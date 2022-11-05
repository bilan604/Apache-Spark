## Run unit tests
There are multiple ways to run unit tests, as shown below. Spark unit tests takes reletatively longger time to start and run, but should finish at minutes level.

### Using VS Code GUI
1. In dev container, open Testing tab
2. Follow GUI icons

### Using terminal
1. In Terminal of dev container, go to root directory of this project.
2. Run the following commands.
    ```sh
    pytest --cov=. --cov-config=.coveragerc tests \
        --cov-report=html \
        --cov-report=xml \
        --cov-report term
    ```    
3. When the tests finish, find coverage report under [coverage_html_report](coverage_html_report) folder, and open [index.html](coverage_html_report) via Web browser.  

## Data Scrapping Data Samples:
```yaml
    {
        0: {
        'rater': 'Jul 16, 2022 - Anonymous Employee',
        'pros': 'Good Company for technical growth',
        'cons': 'No cons, great company to work for.',
        'rating': '5.0'
        },
       1: {
       'rater': 'Jun 24, 2022 - Data Scientist',
        'pros': 'good work culture,flexible work hours',
        'cons': 'not much to say about improvements',
        'rating': '5.0'
        },
       2: {
       'rater': 'Jun 14, 2022 - Software Engineer',
        'pros': 'Very nice place to work',
        'cons': 'No cons at this moment',
        'rating': '5.0'
        },
       3: {
       'rater': 'Jun 9, 2022 - SEO Executive',
        'pros': 'Everything is good, Great work environment, Zero work pressure and Good culture.',
        'cons': 'Nothing is bad all these things is manage properly.',
        'rating': '5.0'
        },
       4: {
       'rater': 'May 27, 2022 - Data Scientist',
        'pros': "If you don't have enough knowledge and experience or you just can't focus on one thing, they'll help you. My trainers were very good and I am absolutely sure that the risk was worth taking. Everyone among my teammates got their foot in IT.",
        'cons': "Although the trainings are remote, you can't combine them even with any other part time job - sometimes you have no time for lunch. No life-work balance at all for the duration of the program (almost 10 months)",
        'rating': '5.0'
        },
       5: {
       'rater': 'Apr 28, 2022 - Machine Learning Engineer',
        'pros': 'Very good work environment and handsome salary',
        'cons': 'I did not find any negative part in this company.',
        'rating': '5.0'
        },
       6: {
       'rater': 'Apr 13, 2022 - Data Scientist',
        'pros': "before i start the review wanted to write a piece of a  poem\r\nSuccess is counted sweetest\r\nBy those who ne'er succeed.\r\n\r\n\r\ni Dont write reviews much but writing now as it a review well deserved. After being ignoredby like tens of companies after interviewing with them I was contacted ny a person from synergisticit who told about the program and told me it cost like 30 grand. I thought the person was crazy expecting me to shell that much amount when i had already spent a ton of $$$ for my bachelors .\r\n\r\nDid some research , read some stuff looked at reviews and stuff (felt undecided still) contacted some of their alumni over linkedin and then i decided to take the plunge. Paid like 10 grand upfront by maxing out 2 of my credit cards and some savings as i felt it was worth taking the plunge. I figured if I invested 10k and after 6 months or so got a job for 75k or more it would be worth it and i could recover my investment.\r\n\r\ntook me 7 months in total to complete everything get prepped up and get 2 job offers one at 105k and another at 110k  and I for once made the right decision which was a big decision and a big investment.\r\n\r\nI remember i had tears of joy when i got the email from the 1st employer about the job offer. God bless synergisticit and Ashish for helping me start on my technology career.\r\n\r\nThe pain which i felt when i was rejected by so many employers and the joy i had when i finally got my offer can only be surmised by the emily blunt poem that you only appreciate success only and only once you have faced so many setbacks and defeats.\r\n\r\nNot going to recommend anyone about what to do or not to do. hundreds of places maybe thousands in our country for doing what synergisticit does but i guess Ashish summed it up best when he said its not what you do what matters but how you do it and how you execute and what leads to the final outcome. If after doing education or whatever you dont get a job then the whole process is just a waste of time.\r\n\r\nI am glad with me it was not. They delivered what they promised and they are honest . I am sure there may be others out there still after speaking to maybe like 30 of my friends i found them to be the best in terms of the end result.\r\n\r\nI wish synergisticit the best and the best to whosoever joins them as their motto is rightly so - the best programmers in the bay area. period",
        'cons': 'their pitch to have candidates join their program can be improved. They also had some jobs posted which kind of made it weird. If they have a good advertising program like other bootcamps do they will get thousands of candidates as their results are the best amongst everyone at least I am aware of . Even people from stanford joined synergistict but maybe they dont so many people.',
        'rating': '5.0'
        },
       7: {
       'rater': 'Mar 9, 2022 - Full Stack Web Developer',
        'pros': 'Great place to work! The staffs are great!',
        'cons': 'Sometimes the progress is too fast!',
        'rating': '5.0'
        },
       8: {
       'rater': 'Mar 9, 2022 - Data Scientist',
        'pros': 'Great place to hone your skills and work on varied projects. Will get you ready with experience for most industries looking for data scientists.',
        'cons': 'can take around an year depending on previous experience',
        'rating': '5.0'
        },
       9: {
       'rater': 'Mar 2, 2022 - Trainee',
        'pros': "It's been so hard for me to find a job after graduation because of covid. SynergisticIT helped me a lot. And I got my certificates and a really decent job.",
        'cons': 'It could be really hard and busy sometimes. Be stern and study hard. There could be a lot of assignments.',
        'rating': '5.0'
        }
    }
```
  
```yaml
[
    {
    'link': 'https://www.amazon.jobs/en/jobs/2155085/penetration-testing-engineer',
    'summary': '"Job summaryDo you enjoy finding unique security issues? Do you enjoy protecting customers at scale? On the AWS Penetration Testing team, you will be responsible for the delivery of continuous assessments. You will be asked to solve complex technology problems, build tools to automate your way out of manual efforts, and influence the way Amazon services respond to and mitigate threats.Our team is responsible for the manual assessment of all products, services and software released by AWS. We specialize in digging deep to find security issues that static analysis tools can’t, and write the tooling to help with these goals whenever possible. The AWS surface area is large and diverse, and we use results found in manual analysis to help improve our enterprise-wide automation to proactively spot and fix potential security issues to protect customers.We are looking for a Security Engineer to help ensure our services, applications, and websites are designed and implemented to the highest security standards. You will be responsible for application, and hardware penetration testing. You will be responsible for automating repetitive tasks using various scripting languages. You will be responsible for influencing Amazon services through the creation of threat mitigation plans. You will work directly with internal teams to solve challenging software problems. Responsibilities: Manually audit the source code of web services and software authored in house by AmazonWrite proof of concept code to demonstrate the severity of a potential security issueProvide clear communication on issues to developers that suggest and help to test the fixPartner with AWS developers to drive improvement in application security as a result of security review engagementsProvide actionable long term risk mitigation guidanceConduct independent vulnerability research pertaining to AWS relevant technologiesFor more information, please reach out to to AWS Recruiter, Abdul Shohatti (ashohatt@amazon.com)" /><meta property',
    'args': [
    '{"value":true,"is_active":true,"is_overridden":true,"default_value":false}',
    '{"logo_class_name":"logo","show_check_app_status_link":true,"show_applications_link":false,"show_referrals_link":false,"show_profile_link":false,"show_culture_menu_link":true,"show_diversity_link":true,"show_location_link":true,"show_resources_menu_links":true,"faq_link":"/faqs"}',
    '{"rootPath":"/en","keyword_typeahead":"/en/keyword_typeahead","locationSearch":true,"logoClass":"logo"}',
    '{"identifier":"southern-california-metropolitan-area","title":"Southern California Region, California","type":"location"}', '{"country_code":"US","country_name":"United States","job_id":"2155085"}',
    '{"locale":"en","available_locales":["cs","de","en","en-gb","es","fr","it","jp","pl","pt","zh"],"default_locale":"en","relative_url":""}'
        ]
    },    
    {
    'link': 'https://www.amazon.jobs/en/jobs/1164273/penetration-testing-engineer', 
    'summary': None, 
    'args': [
    '{"value":true,"is_active":true,"is_overridden":true,"default_value":false}', 
    '{"logo_class_name":"logo","show_check_app_status_link":true,"show_applications_link":false,"show_referrals_link":false,"show_profile_link":false,"show_culture_menu_link":true,"show_diversity_link":true,"show_location_link":true,"show_resources_menu_links":true,"faq_link":"/faqs"}',
    '{"rootPath":"/en","keyword_typeahead":"/en/keyword_typeahead","locationSearch":true,"logoClass":"logo"}',
    '{"identifier":"southern-california-metropolitan-area","title":"Southern California Region, California","type":"location"}', '{"country_code":"US","country_name":"United States","job_id":"1164273"}',
    '{"locale":"en","available_locales":["cs","de","en","en-gb","es","fr","it","jp","pl","pt","zh"],"default_locale":"en","relative_url":""}'
        ]
    }, 
    {
    'link': 'https://www.amazon.jobs/en/jobs/2155085/penetration-testing-engineer',
    'summary': '"Job summaryDo you enjoy finding unique security issues? Do you enjoy protecting customers at scale? On the AWS Penetration Testing team, you will be responsible for the delivery of continuous assessments. You will be asked to solve complex technology problems, build tools to automate your way out of manual efforts, and influence the way Amazon services respond to and mitigate threats.Our team is responsible for the manual assessment of all products, services and software released by AWS. We specialize in digging deep to find security issues that static analysis tools can’t, and write the tooling to help with these goals whenever possible. The AWS surface area is large and diverse, and we use results found in manual analysis to help improve our enterprise-wide automation to proactively spot and fix potential security issues to protect customers.We are looking for a Security Engineer to help ensure our services, applications, and websites are designed and implemented to the highest security standards. You will be responsible for application, and hardware penetration testing. You will be responsible for automating repetitive tasks using various scripting languages. You will be responsible for influencing Amazon services through the creation of threat mitigation plans. You will work directly with internal teams to solve challenging software problems. Responsibilities: Manually audit the source code of web services and software authored in house by AmazonWrite proof of concept code to demonstrate the severity of a potential security issueProvide clear communication on issues to developers that suggest and help to test the fixPartner with AWS developers to drive improvement in application security as a result of security review engagementsProvide actionable long term risk mitigation guidanceConduct independent vulnerability research pertaining to AWS relevant technologiesFor more information, please reach out to to AWS Recruiter, Abdul Shohatti (ashohatt@amazon.com)" /><meta property', 
    'args': [
    '{"value":true,"is_active":true,"is_overridden":true,"default_value":false}', 
    '{"logo_class_name":"logo","show_check_app_status_link":true,"show_applications_link":false,"show_referrals_link":false,"show_profile_link":false,"show_culture_menu_link":true,"show_diversity_link":true,"show_location_link":true,"show_resources_menu_links":true,"faq_link":"/faqs"}',
    '{"rootPath":"/en","keyword_typeahead":"/en/keyword_typeahead","locationSearch":true,"logoClass":"logo"}',
    '{"identifier":"southern-california-metropolitan-area","title":"Southern California Region, California","type":"location"}', '{"country_code":"US","country_name":"United States","job_id":"2155085"}',
    '{"locale":"en","available_locales":["cs","de","en","en-gb","es","fr","it","jp","pl","pt","zh"],"default_locale":"en","relative_url":""}'
        ]
    }, 
    {
    'link': 'https://www.amazon.jobs/en/jobs/2004839/offensive-security-engineer-aws', 
    'summary': '"Job summary**This role is open to alternative locations including: New York, NY – Boston, MA – Seattle, WA - Vancouver, BC Canada - Herndon, VA – Arlington, VA – Baltimore, MD – San Luis Obispo, CA – San Diego, CA. The Amazon Web Services (AWS) Security team is looking for a Security Engineer who has a strong passion for security-at-scale. You will be on a team responsible for the design &amp;amp; implementation of continuous assessments and technology helping teams maintain insight to the integrity of their development, deployment, monitoring, and response processes.AWS Security is on the cutting edge of many security issues for a wide variety of platforms and technologies including cloud services, Internet of things (IoT), identity and access management, mobile devices, virtualization and custom hardware, all operating at massive scale.AWS Security is looking for a Security Engineer to help ensure our services, applications, and websites are designed and implemented to the highest security standards. You will be responsible for designing and implementing workflows that integrate with multiple services, automation that removes humans from the loop, and correlation &amp;amp; analysis platforms that function at the scale of AWS. You will work directly with internal teams to solve challenging software problems and influence how other teams interface with your architectures.You must produce results in the face of ambiguity and imperfect knowledge, and foster constructive dialogue and drive resolution when faced with disagreement. You are considered a technical leader on your team. You work efficiently and routinely deliver the right things with limited guidance. Your work focuses on ambiguous problem areas in existing or new hardware and software initiatives. You take a long term view of your team’s processes &amp;amp; software, understanding how it fits into the business. You proactively fix architectural deficiencies and/or propose larger project scopes, which may require the work of a team. You split that work into parallel tasks that can be performed by you and others and then reassembled successfully.Amazon’s Leadership Principles of “Dive Deep”, “Earn Trust”, “Deliver Results”, and “Invent and Simplify” will be called upon daily. A successful candidate will need a combination of troubleshooting, technical, and communication skills, as well as the ability to handle a mix of complex decisions.CORE RESPONSIBILITIES- Contribute to the design, implementation, and execution of security review and test methodologies for the recurring and holistic testing of a critical group of AWS production services. Ensure remediation of risks by partnering with service teams.Perform design review, threat modeling, security review, penetration testing, and red teaming on production systems for AWS services.Scope and perform penetration testing &amp;amp; vulnerability research of complex proprietary software and hardware for AWS services.Work closely with the AWS Security teams to develop large scale, cutting edge, testing, monitoring, remediation, and analytics solutions.Work closely with other internal development teams across AWS Security to create comprehensive security tooling and functional improvements at scale.Demonstrate “exceptional” judgment, integrity, business acumen, and communication skills.Prepare and present detailed, written technical information for internal and external audiences.Inclusive Team Culture Here at AWS, we embrace our differences. We are committed to furthering our culture of inclusion. We have ten employee-led affinity groups, reaching 40,000 employees in over 190 chapters globally. We have innovative benefit offerings, and host annual and ongoing learning experiences, including our Conversations on Race and Ethnicity (CORE) and AmazeCon (gender diversity) conferences. Amazon’s culture of inclusion is reinforced within our 16 Leadership Principles, which remind team members to seek diverse perspectives, learn and be curious, and earn trust.  Work/Life Balance Our team puts a high value on work-life balance. It isn’t about how many hours you spend at home or at work; it’s about the flow you establish that brings energy to both parts of your life. We believe striking the right balance between your personal and professional life is critical to life-long happiness and fulfillment. We offer flexibility in working hours and encourage you to find your own balance between your work and personal lives.  Mentorship &amp;amp; Career Growth Our team is dedicated to supporting new members. We have a broad mix of experience levels and tenures, and we’re building an environment that celebrates knowledge sharing and mentorship. We care about your career growth and strive to assign projects based on what will help each team member develop into a better-rounded professional and enable them to take on more complex tasks in the future.Please contact Robert Cahill (cahirobe@amazon.com) for more information." /><meta property', 
    'args': [
    '{"value":true,"is_active":true,"is_overridden":true,"default_value":false}', 
    '{"logo_class_name":"logo","show_check_app_status_link":true,"show_applications_link":false,"show_referrals_link":false,"show_profile_link":false,"show_culture_menu_link":true,"show_diversity_link":true,"show_location_link":true,"show_resources_menu_links":true,"faq_link":"/faqs"}',
    '{"rootPath":"/en","keyword_typeahead":"/en/keyword_typeahead","locationSearch":true,"logoClass":"logo"}', 
    '{"identifier":"systems-quality-security-engineering","title":"Systems, Quality, \\u0026 Security Engineering","type":"category","label":"Systems, Quality, \\u0026 Security Engineering"}',
    '{"country_code":"US","country_name":"United States","job_id":"2004839"}',
    '{"locale":"en","available_locales":["cs","de","en","en-gb","es","fr","it","jp","pl","pt","zh"],"default_locale":"en","relative_url":""}'
        ]
    }, 
    {
    'link': 'https://www.amazon.jobs/en/jobs/2004839/offensive-security-engineer-aws', 
    'summary': '"Job summary**This role is open to alternative locations including: New York, NY – Boston, MA – Seattle, WA - Vancouver, BC Canada - Herndon, VA – Arlington, VA – Baltimore, MD – San Luis Obispo, CA – San Diego, CA. The Amazon Web Services (AWS) Security team is looking for a Security Engineer who has a strong passion for security-at-scale. You will be on a team responsible for the design &amp;amp; implementation of continuous assessments and technology helping teams maintain insight to the integrity of their development, deployment, monitoring, and response processes.AWS Security is on the cutting edge of many security issues for a wide variety of platforms and technologies including cloud services, Internet of things (IoT), identity and access management, mobile devices, virtualization and custom hardware, all operating at massive scale.AWS Security is looking for a Security Engineer to help ensure our services, applications, and websites are designed and implemented to the highest security standards. You will be responsible for designing and implementing workflows that integrate with multiple services, automation that removes humans from the loop, and correlation &amp;amp; analysis platforms that function at the scale of AWS. You will work directly with internal teams to solve challenging software problems and influence how other teams interface with your architectures.You must produce results in the face of ambiguity and imperfect knowledge, and foster constructive dialogue and drive resolution when faced with disagreement. You are considered a technical leader on your team. You work efficiently and routinely deliver the right things with limited guidance. Your work focuses on ambiguous problem areas in existing or new hardware and software initiatives. You take a long term view of your team’s processes &amp;amp; software, understanding how it fits into the business. You proactively fix architectural deficiencies and/or propose larger project scopes, which may require the work of a team. You split that work into parallel tasks that can be performed by you and others and then reassembled successfully.Amazon’s Leadership Principles of “Dive Deep”, “Earn Trust”, “Deliver Results”, and “Invent and Simplify” will be called upon daily. A successful candidate will need a combination of troubleshooting, technical, and communication skills, as well as the ability to handle a mix of complex decisions.CORE RESPONSIBILITIES- Contribute to the design, implementation, and execution of security review and test methodologies for the recurring and holistic testing of a critical group of AWS production services. Ensure remediation of risks by partnering with service teams.Perform design review, threat modeling, security review, penetration testing, and red teaming on production systems for AWS services.Scope and perform penetration testing &amp;amp; vulnerability research of complex proprietary software and hardware for AWS services.Work closely with the AWS Security teams to develop large scale, cutting edge, testing, monitoring, remediation, and analytics solutions.Work closely with other internal development teams across AWS Security to create comprehensive security tooling and functional improvements at scale.Demonstrate “exceptional” judgment, integrity, business acumen, and communication skills.Prepare and present detailed, written technical information for internal and external audiences.Inclusive Team Culture Here at AWS, we embrace our differences. We are committed to furthering our culture of inclusion. We have ten employee-led affinity groups, reaching 40,000 employees in over 190 chapters globally. We have innovative benefit offerings, and host annual and ongoing learning experiences, including our Conversations on Race and Ethnicity (CORE) and AmazeCon (gender diversity) conferences. Amazon’s culture of inclusion is reinforced within our 16 Leadership Principles, which remind team members to seek diverse perspectives, learn and be curious, and earn trust.  Work/Life Balance Our team puts a high value on work-life balance. It isn’t about how many hours you spend at home or at work; it’s about the flow you establish that brings energy to both parts of your life. We believe striking the right balance between your personal and professional life is critical to life-long happiness and fulfillment. We offer flexibility in working hours and encourage you to find your own balance between your work and personal lives.  Mentorship &amp;amp; Career Growth Our team is dedicated to supporting new members. We have a broad mix of experience levels and tenures, and we’re building an environment that celebrates knowledge sharing and mentorship. We care about your career growth and strive to assign projects based on what will help each team member develop into a better-rounded professional and enable them to take on more complex tasks in the future.Please contact Robert Cahill (cahirobe@amazon.com) for more information." /><meta property', 
    'args': [
    '{"value":true,"is_active":true,"is_overridden":true,"default_value":false}', 
    '{"logo_class_name":"logo","show_check_app_status_link":true,"show_applications_link":false,"show_referrals_link":false,"show_profile_link":false,"show_culture_menu_link":true,"show_diversity_link":true,"show_location_link":true,"show_resources_menu_links":true,"faq_link":"/faqs"}', '{"rootPath":"/en","keyword_typeahead":"/en/keyword_typeahead","locationSearch":true,"logoClass":"logo"}',
    '{"identifier":"systems-quality-security-engineering","title":"Systems, Quality, \\u0026 Security Engineering","type":"category","label":"Systems, Quality, \\u0026 Security Engineering"}', '{"country_code":"US","country_name":"United States","job_id":"2004839"}', 
    '{"locale":"en","available_locales":["cs","de","en","en-gb","es","fr","it","jp","pl","pt","zh"],"default_locale":"en","relative_url":""}'
        ]
    },
    {
    'link': 'https://www.amazon.jobs/en/jobs/1932828/mobile-security-engineer-offensive-security-penetration-testing', 
    'summary': '"Job summaryAmazon’s Information Security Penetration Testing Team is seeking a Mobile Security Engineer to help keep Amazon secure for its customers. In this role, you will attack Amazon’s mobile services, mobile applications and hardware (IOS &amp;amp; Android) to discover security issues and report them to our internal technology teams. This position will provide you with challenging opportunities, both technologically and as a leader, but will also be a great deal of fun if hacking Amazon alongside a team of highly skilled individuals sounds exciting to you.A Security Engineer at Amazon is expected to be strong in multiple domains. Engineers in this role work closely with teams throughout Information Security, as well as provide technical leadership and advice to teams and leaders throughout Amazon. You will be in direct contact with teams in a variety of business verticals, giving you first hand knowledge about how Amazon is built and how it operates at a deep, technical level. Additionally, you will leverage the knowledge you gain about Amazon to find new ways to break services, processes, and technologies throughout the company.Engineers in this role must show exemplary judgment in making technical trade-offs between short-term fixes and long-term security and business goals. You will demonstrate resilience and navigate ambiguous situations with composure and tact. You will be expected to provide thought leadership for the organization as you discover, invent, and innovate throughout the course of your duties. Above all else, a strong sense of customer obsession is necessary to focus on the ultimate goal of keeping Amazon and its customers secure.Key job responsibilities* Conducting high quality application penetration tests independently, or as part of a team* Creating detailed engagement plans and thoroughly documenting findings, gaps, and remediation recommendations* Contributing to team tooling, innovation, and improvements* Communicating and collaborating with partner teams, service owners, Information Security, and senior leadership to influence, prioritize, and drive the resolution of discovered security findings" /><meta property', 
    'args': 
        [
        '{"value":true,"is_active":true,"is_overridden":true,"default_value":false}', 
        '{"logo_class_name":"logo","show_check_app_status_link":true,"show_applications_link":false,"show_referrals_link":false,"show_profile_link":false,"show_culture_menu_link":true,"show_diversity_link":true,"show_location_link":true,"show_resources_menu_links":true,"faq_link":"/faqs"}',
        '{"rootPath":"/en","keyword_typeahead":"/en/keyword_typeahead","locationSearch":true,"logoClass":"logo"}',
        '{"identifier":"systems-quality-security-engineering","title":"Systems, Quality, \\u0026 Security Engineering","type":"category","label":"Systems, Quality, \\u0026 Security Engineering"}', '{"country_code":"US","country_name":"United States","job_id":"1932828"}',
        '{"locale":"en","available_locales":["cs","de","en","en-gb","es","fr","it","jp","pl","pt","zh"],"default_locale":"en","relative_url":""}'
        ]
    }
]
```
