# Ha, Phan
######Ho Chi Minh City, 70500, Vietnam
######Cellphone: (+84) 129-824-1087
######Email: [thanhha.work@gmail.com](mailto:thanhha.work@gmail.com)
######Skype: hatphan


*This CV is composed in Mark-down with  ![heart](http://i.imgur.com/FCJaHj0.png)*

##About me

- A motivated software architect with strong commitment to opensource technologies, particularly PHP and Symfony framework. Check out my [PHP-RAGE4](https://github.com/haphan/php-rage4dns) project on Github

- A full-stack developer that can hack his way from User Interface to Coding business logics and finally setting up production servers. See my [server deployment script](https://gist.github.com/haphan/84eb9755ddd06f09326b) on Gist

- A contributor to Symfony, Doctrine, Drupal and few other OSS projects.

##Fun facts

- I started using Symfony 1 then left to build my own PHP framework because there were too many *magics* in Symfony back then. (Yes! everybody has a personal framework right?). Symfony 2 proves to provide more modular architecture and transparent roadmap which made my come back. Since then I am in a love-and-hate relationship with Symfony2 (read Convention over Configuration, Dependency injection, Form API, YML vs Annotation,  etc..).

- A Micro$oft (and IE, and Outlook) hater. Mac for work and Debian for servers please!

- 3 shots of moka espresso everyday or my brain does not work.

- You may often see me following [@fabpot](https://twitter.com/@fabpot), [@eranhammer](https://twitter.com/eranhammer)  [@igorwesome](https://twitter.com/igorwesome), reading [Coding Horror](http://blog.codinghorror.com), [A List Apart](http://alistapart.com), and laughing out-loud whenever I heard someone complaints [node.js leaks memory](https://www.joyent.com/blog/walmart-node-js-memory-leak).

- Co-founded a start-up company with a friend doing digital marketing. I failed miserably! What remains important are lessions learnt from that failure though.

##Education

1. MSc in Computer Science, The University of Manchester, U.K.
2. BS in IT, Vietnam National University, Vietnam.

##Certificates

1. Scrum Master by Scrum.org
2. PMP (Professtional Project Management) by PMI

##Professional Experience

####Nov 2013 - Present: Software Architect, ICT Services, RMIT University

Perform expert-level systems design and development. Inform and advise management on technical and organizational impacts on RMIT information systems. Ensure the consistency and maintainability of integrated products that support RMIT’s business.

Provide guidance and work leadership to less experienced system engineers. Actively conduct trainings to team members with current knowledge of relevant technology and tools.

######Key projects:

1. **Blackboard Shared LMS Integration**. This project is to replace self-hosted instance of Blackboard 8 in RMIT Saigon South Campus and allow RMIT Vietnam to integrate with Melbourne’s shared-instance of Blackboard. Project delivers an integration layer that synchronises data between RMIT Vietnam Student Record Systems and RMIT Melbourne Blackboard.

2. **Events Management System**. Initially built to manage guest and invitation for Graduation day, EMS is an online ticketing service and allows event organizers to plan, set up tickets and promote events, and publish them across social-networking platform. EMS also deeply integrates with RMIT CRM, Google calendar, Sengrid.

   - Primary features: Manage registration (Send out RSVP, confirmation, ticket, ...), Check in/out service, Ticket generation following custom templates (barcode, QRcode), Measure Engagement and Statistics, Create team to manage event during the day.

3. **Intranet transformation** This is an on-going project which bringing our 4 years old intranet a brand new look. Key features from our Public Website project like editorial workflow has been shared to this new intranet.

####Mar 2011 to Nov 2013: Senior Web Developer, ICT Services, RMIT University.

Participate in business applications design and development. My responsibilities are to ensure IT application solutions delivered; meet stack-holders’ business requirements and RMIT University strategies.

As a senior developer, I constantly lead the technical aspects of new projects and make important technical decisions to ensure a high quality product.

######Key projects:

**Enterprise Applications Solution** Develop and maintain 15 enterprise apps that help improving the effectiveness across departments. Key apps are Procurement, Inventory, Outage Notification, Tender, Legal Office. This project is built on top of a Business Application Platform (BAP) which standardises authentication, user roles managements processes for apps hosted on top of this platform.

- The technology: Symfony2 LTS, Memcache, Behance, MySQL, Jenkins CI, CAS SSO, Responsive UI, ESB integration.
- The challenge : Each app is modular and can be cloned in seconds for a department (thanks to the BAP platform), serving 150 active users for their business critial purposes. Deployment process is non-interrupting.

**RMIT Vietnam Public website transformation** This project is to redevelop and migrate existing content from a legacy, commercial CMS that no longer being supported by software vendor. My responsibility is to justify the use of Drupal as a CMS, provide architectural design, develop and maintain CMS stability upon deployed.

- The stack: Drupal 7, Drush, Jenkins CI, Memcache, Varnish, Reverse proxy.
- The challenge: Continuously migrate old content into the new platform so that there is no content gap when new system goes live. The editorial workflow is also complex to fit the needs of end users.


####Dec 2009 to Oct 2010: Team Lead Developer, Penta Solutions and Technologies, LLC.
Leading software development/outsourcing team consists of 5 developers. The company’s clients are U.S. and Canada software agencies. My responsibilities are to ensure software quality standard and on-time delivery. Liaise with Account manager and directly communicate with customers using agile development.

####Apr 2009 to Nov 2009: System Engineer, VNPT Corporation
Working on smart-home solution project: providing early warnings and allows householders to remotely control and monitor electronic home appliances. The project involves interfacing with network-enabled electronic sensors via TCP/UDP. Alarms from sensors are to be dispatched by SMS.


##Personal projects

1. [Moveek.com](https://moveek.com) - A website of upcoming movie reviews and live schedule of near-by box offices. Running off a 512MB DigitalOcean droplet (recently I had to scale up the instance to 1GB due to bandwidth reason). Serving 30K+ visits daily without a hiccup.

	Technology stack: *Symfony2, nginx, memcache, MonitikCDN.*

2. [Rage4DNS Console Tool](https://github.com/haphan/php-rage4dns) Rage4DNS is a geo name servers as a service. My project is to provide intergration tool with Rage4DNS.

	Technology stack: *Symfony Components, RESTful web services, SensioLabs Insights.*

3. **Monitik CDN** (Not yet published) A private CDN built on top of Rage4DNS, Varnish, Nginx and 25 cloud VPS around the world. Using Rage4DNS Console Tool to dynamically direct requests to nearest server.

##Technical stacks

1. **Language and Frameworks**: PHP (Symfony2), Zend2, Node.js. Occationally Django, Lua and Ruby.
1. **Cloud platform**: DigitalOcean, AWS, Heroku, Pagodabox, S3, Route53, Rage4DNS.
1. **Monitoring tools**: NewRelic, QRadar, Cacti, Munin, Observium.
1. **High Performance**: HAProxy, NGINX, Varnish, Corosync, Redis, Memcache.
1. **CMS**: Drupal (see [www.rmit.edu.vn](http://www.rmit.edu.vn)), Wordpress.
1. **Front-end**: Bower, Require.js, Grunt, HTML5. See my microsite for RMIT [http://www.rmit.edu.vn/m](http://www.rmit.edu.vn/m)
1. **OS flavours**: Debian, RHEL, Mac.
1. **Development tools**: GIT, Jenkins, MAMP Pro, Behance, Composer.

##Reference

1. **Ousmane Diallo**, Application Delivery Manager, IT Services, RMIT University [ousmane.diallo@rmit.edu.vn](mailto:ousmane.diallo@rmit.edu.vn)

2. **Stephane Masse**, Director, IT Services, RMIT University, [stephane.masse@rmit.edu.vn](mailto:stephane.masse@rmit.edu.vn)


