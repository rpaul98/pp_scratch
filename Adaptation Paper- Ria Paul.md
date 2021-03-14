Citation method: MLA

Ria Paul

# Open-Source Ecology

# Introduction

Open Source Ecology (OSE), founded in 2003 by Marcin Jakubowski, is a collaborative community adapting open-source ideologies to &quot;increase innovation through open collaboration&quot; (Jakubowski, 2016). The OSE community is working towards sustainable civilizations and combatting material scarcity around the world. They are doing this by developing open-source blueprints for the Global Village Construction Set (GVCS). The GVCS is a set of 50 sustainable and low-cost Industrial machines made from cheap and readily available materials. The machines identified as a part of the GVCS are maintained to be everything needed to support a small civilization. By using open-source philosophies to guide the development of the GVCS, their goal is to create an open and more inclusive economy.

Traditionally, open-source principles are primarily applied to software projects (called Free and Libre Open Source Software, or FLOSS). OSE, however, is applying it to hardware. This paper seeks to analyze OSE&#39;s collaboration and management structure to investigate how open hardware at OSE relates to open-source software. This is done by investigating governance structure, methods of collaboration, workflows, etc. Information about OSE was obtained through the OSE Wiki, OSE official website, and an interview with a developer on the team, Melanie Allen.

# OSE Members

The OSE community is comprised of volunteers who are farmers, engineers, designers, architects, and more. These volunteers are either &quot;OSE Contributors&quot; or &quot;OSE Developers&quot;. OSE Contributors are ad-hoc contributors who can make edits to the Wiki, engage in discussion boards, or provide financial support. OSE Developers, on the other hand, are official members who work on designing blueprints and building the machinery.

Similar to traditional open-source projects, anyone is welcome to become an OSE Contributor and share their ideas and/or knowledge. However, in contrast to traditional open-source, the OSE Developers operate in a manner more comparable to processes in a firm. They are organized in dedicated teams and are selected based on an application and interview process. If they pass the interview, they then have to take a developer test designed to assess their proficiency and ability to use the necessary design software. However, the most important requirement for becoming a developer is an eagerness to learn and an open mind.

OSE Developers are required to contribute 10 hours a week and make a 90-day commitment to the project. Each 90-day period is a development cycle, the end of which should be a product release. The developers work according to the OSE Roadmap, which outlines milestones for the development of GCVS machinery.

Developers work on the machine blueprints mainly using FreeCAD, which is open-source software for designing structures and machines. The OSE Wiki includes a page dedicated to tutorials on FreeCAD as well as the expected workflow.

# Collaboration Infrastructure

## Collaboration Mediums

According to Crowston et al. (2019), documentation is a key tool that drives coordination and collaboration in open-source projects. Specifically, they mention that documentation creates the awareness that is necessary to support collaborative work. Along similar lines, Shah (2005) claims that documentation also serves to attract and support new users. In the case of OSE, this documentation is provided by the official Open Source Ecology Wiki. This Wiki has pages detailing the GVCS, workshops, links to various materials/tools for construction, tutorials, general information about OSE, developer logs, and more. According to Melanie, the Wiki is also the primary source of communication among members of the community. Even though OSE is comprised of a dedicated team of selected developers to design the machines, anyone can contribute to and/or use the information from these Wiki pages.

The Wiki also provides links to a mailing list as well as the OSE blog/website. This website gives further information about the community, its goals, its history, how to become involved, etc. The community also has its own Facebook group, Twitter account, and YouTube channel. Through these mediums, the members of the community can stay connected and ideas/skills for hardware innovation can be spread to the public.

## Governance Structure

Open-source projects can operate under a range of different governance models. One such model is the &quot;benevolent dictatorship&quot;, in which the head of the organization navigates the project, while the rest of the community makes contributions under the dictator&#39;s specifications. (Gardler, Hanganu, 2010). OSE adopts this governance model and is run under Marcin Jakubowski, who is the founder and executive director. Marcin along with the board of directors is responsible for the OSE Roadmap, which specifies the strategic milestones for the project. The rest of the community is responsible for carrying out tasks delegated to them by Marcin and the board.

## Agile Development

Agile development, the idea of adaptive and flexible collaboration, is very popular in software development. One aspect of Agile development is scrum, which is a collaboration method in which team members regularly check in with each other&#39;s progress. It is used to &quot;bring transparency and encourage informal communication&quot; (Singhal et al, 2014). The developers do this through personal log pages on the Wiki. These logs detail what they have finished, what they are currently working on, and anything that is currently blocking their progress. In this way, developers can keep up to date with each other and coordinate their efforts.

## Build Camps and Workshops

One key difference between FLOSS and open hardware is that open hardware comes with costs. To help fund operations, OSE hosts build camps as another method of collaboration and open innovation. They are available to the public for a tuition fee, which further helps to support OSE. During these camps, participants spend around 10 days learning how to build a specific machine. They are given construction sets and are taught how to build and calibrate the machine throughout the first few days of the camp. The rest of the camp is often dedicated to classroom sessions learning about design principles and how to use FreeCAD.

# Workflow

&quot;Software processes comprise many steps; coding is followed by building, integration testing, system testing, deployment, operations, among others….Software project ecosystems such as GitHub provide a new opportunity in this regard: one can readily find large numbers of projects in various stages of process integration and automation&quot; (Vasilescu et. Al, 2015). The official term for process integration and automation is _Continuous Integration_, in which modular code changes are automatically merged, built, and tested into a separate version of the main branch. According to Vasilescu, continuous integration results in major productivity gains in open-source software projects because it provides more confidence that a change works. Before a change is merged into the _official_ main branch, it is guaranteed to pass the required tests.

The workflow for OSE, on the other hand, is much less coupled together than the ones seen in FLOSS and the idea of continuous integration doesn&#39;t apply well here. This is the case for two key reasons. First, OSE is creating a _set_ of products rather than one large product. In software, features are much more interconnected and there is more concern of having one change breaking the build for the entire product. This is not as much of an issue with OSE, where the development of one product will not affect a separate one in the set.

The second reason is that with hardware, there are two phases: the designing phase and the building/testing phase. During the design phase, developers use FreeCAD and KitCAD software to collaboratively design the blueprints for the machines. During the build/test phase, some members go down to a site owned by OSE called Factor e Farm to physically build the machines. Compared to software, the build/test phase is relatively disconnected from the design phase. It requires members to work together in person using physical materials which have a cost. Because of this, the testing and validation for hardware in OSE don&#39;t provide free and immediate feedback as it can with software.

## Design phase: FreeCAD and KitCAD

Although the entire OSE workflow has many differences to software workflows, the design phase on its own is very similar. Developers use FreeCAD, which is software used to design structures, as well as KitCAD, which is software used to design circuits. With these software products, developers can create small modular designs of parts and then merge their work to create the final machine blueprint. The software can also help with preliminary testing such as validating whether the machine would structurally sound before it is physically built. This procedure is very similar to the collaborative processes seen through branching and merging seen in systems such as GitHub.

## Build/test phase: Factor e Farm

The build/test phase takes place at Factor e Farm, a 30-acre plot of land in Missouri purchased by OSE. As described by Melanie, FEF serves as a &quot;flagship hackerspace&quot;. The idea of the GVCS is that it could serve as a sort of &quot;civilization in a box&quot; that provides everything necessary to create and support a small civilization with local resources. At FEF, a few select members are experimenting with how a small self-sufficient civilization could be built using the GVCS blueprint. Through the documentation of FEF on the Wiki, they are openly sharing their results and findings.

FEF currently has a lot of infrastructures already built using the GVCS for maintaining a small sustainable civilization. Water is supplied to the farm using a Well pump and rainwater catchment and a 1000-gallon tank reservoir. For food, they currently have an orchard with 400 nut, fruit, and berry trees. In the future, they plan to create a forest garden for growing vegetables as another self-sustained food source. They also have a recycling system in place as well as composting bins for food scraps. The main shelter area is called the HabLab and is a house built from Compressed Earth Block and concrete. However, they also have temporary shelters built including tents, huts, and yurts.

Factor e Farm is where the ideas and blueprints come to fruition and the ability of the GVCS to support a civilization is put to the test. Where in open source software projects they have test suites to ensure the software is working as expected according to requirements, OSE has the FEF to assess whether the GVCS lives up to the expectations. The difference, however, is that building and testing tangible products takes time, money, and extra dedication from the members participating.

# Motivations

In open-source software, &quot;a need for software-related improvements drives initial participation. The majority of participants leave the community once their needs are met&quot; (Shah, 2006). In OSE, however, this does not seem to be the case for most developers. According to Melanie, she initially joined because of her interest in permaculture and belief that a civilization construction set &quot;was one of the most critical projects of our day&quot;.

This difference is likely due to two key reasons. The first is that due to the governance structure, developers work on tasks assigned to them, rather than what they would personally like to see implemented. The second is that the end products of OSE are not as likely to be needed by the contributors. The &quot;civilization in a box&quot; is something that would more likely be needed by those living in undeveloped areas. Based on Melanie&#39;s response and the rest of the developer bios on the Wiki, the focus seems to be on joining to help others rather than to satisfy a personal need. According to a few developers, they joined to &quot;contribute to humanity&quot; (OSE Developer Ruslan Krenzler), to &quot;contribute to the necessary change in the way we do things today&quot; (OSE Developer German Crespo), and for &quot;everyone having access to resources to provide a living for one&#39;s self and community&quot; (OSE Developer Chas Murillo).

Shah (2006) further claims that while a majority of participants in FLOSS leave after their needs are met, a small subset remains involved. She notes that &quot;reasons for participation vary, but a critical subset of open source developers – hobbyists – participate because they derive enjoyment from the act of creating code.&quot; This is true for participants in OSE as well, who claim they joined because of personal interests and passions in designing, sustainable building, circuitry, general problem solving, and more. Because OSE is such an interdisciplinary project, people from diverse backgrounds join the project to learn and further develop their skills. From Robert Jeramillo&#39;s developer bio: &quot;It combines nature, people, technology in a practical and holistic way&quot;.

One other motivating factor in OSE is the classification of developers as One Star, Two Star, Three Star, and Four Star devs. This depends on how many hours a developer has worked. Once they have reached 120 hours and completed a 90 day period, they become a One Star Dev. Melanie notes that her goal to be a One Star Dev is one thing that keeps her going in the project.

# Conclusion

Open Source Ecology is a project which exemplifies many of the principles of open-source software. It uses an agile collaboration method, freely publishes all of its designs, provides ample documentation, and allows anyone to contribute voluntarily. Other parallels that can be drawn between OSE and FLOSS are the design workflow using FreeCAD/KitCAD and participant motivations. However, due to OSE producing hardware, there are some fundamental differences as well such as the need to physically build the machinery and the cost associated with it. Another difference is the selection of the OSE Developers, which includes an interview and a test.

Through this exploration of OSE, it is evident that the members are dedicated to its cause and passionate about learning. They value openness and providing the resources for anyone to improve their way of life. By fostering innovation through open source methods, they are coming closer to this goal.

# Citation

Shah, Sonali. &quot;Motivation, Governance &amp; the Viability of Hybrid Forms in Open Source Software Development.&quot; _SSRN_, 9 May 2006

Crowston, Kevin, et al. &quot;Socio-Technical Affordances for Stigmergic Coordination Implemented in MIDST, a Tool for Data-Science Teams.&quot; _Proceedings of the ACM on Human-Computer Interaction_, vol. 3, no. CSCW, 2019, pp. 1–25., doi:10.1145/3359219.

Singhal, Sonia Archana. &quot;Development of Agile Security Framework Using a Hybrid Technique for Requirements Elicitation.&quot; _Communications in Computer and Information Science_, 2011, pp. 178–188., doi:10.1007/978-3-642-18440-6\_22.

Vasilescu, Bogdan, et al. &quot;Quality and Productivity Outcomes Relating to Continuous Integration in GitHub.&quot; _Association for Computing Machinery_, 2015, pp. 805–816., doi:10.1145/2786805.2786850.

Gardler, Ross, and Gabriel Hanganu. _OSS Watch_, 15 Feb. 2010, oss-watch.ac.uk/resources/benevolentdictatorgovernancemodel.

Jakubowski, Marcin. &quot;Main Page.&quot; _Open Source Ecology_, wiki.opensourceecology.org/wiki/Main\_Page.

&quot;Home.&quot; _Open Source Ecology_, 6 Nov. 2020, www.opensourceecology.org/.

# Full Interview with Melanie Allen

1.    What motivated you to join?
&quot;I saw Marcin&#39;s Ted Talk when I was in university. It was almost always in the background of my mind whenever I was thinking about permaculture, society, and manufacturing technology. I always thought that the civilization construction set was one of the most critical projects of our day. I once had dreams to be an engineer, although that didn&#39;t quite pan out for me and I pursued technical communication instead. Furthermore, I remember seeing a wiki that indicated, at least for participation at the farm, people needed to be of sound mind. In my 20s, I had poor mental health from economic struggles and untreated conditions. So, right or wrong, I had disqualified myself and didn&#39;t think much of joining. But one day, more recently and having established myself in mind and career, an old classmate from University got in touch, Michael Altfield. He was asking me about documenting his Buskill.in project but I learned that he had also been in the top two contributors to OSE as an IT administrator. He disabused me of notions that I didn&#39;t have anything to contribute and furthermore pointed me to the wikis about how to become a Developer. I had always wanted to learn FreeCAD and help with documenting an Open Source project, and lockdown had been in effect so I had a lot of time. I&#39;m interested in 3D modelling because I have been interested in 3D printers since before their inception. However my main experience is with OpenSCAD and to be honest I still greatly prefer OpenSCAD....&quot;

2.    How long have you been working with the project?
&quot;July-November 2020 was when I was most active with the project. I took a small break but I would like to start another 90 day session in the near future. &quot;

3.    What motivated you to stay as long as you have?
&quot;I was motivated to become at least a one star dev, which involves volunteering for 90 days and 120 hours. But I also would like to start my own venture. &quot;

4.    How long do you plan to stay?
&quot;OSE has the goal of completing the construction set by 2028. I would like to work on and off until at least then. Then I would like to start my own venture. So you could say, I plan to be a lifer. But as far as actually staying at the farm, I only would like to do that for a quarter, or maybe even a shorter length of time. &quot;

5.    What does a typical workday look like? Is most of your work with FreeCAD?
&quot;When doing Development work, I put in 10 hours a week, mostly on the weekend.I was tasked with documenting the workflows of using the D3D Universal as a pen plotter. Therefore my software stack was mostly Inkscape, Processing, Vokoscreen, Audacity, and Kdenlive.
Marcin and I would discuss the project via email and logs. Logs are critically valued in this project. I would generate files, and he would plot them using his D3D Universal and give me feedback. I would use what I learned to create instructional videos which I uploaded to YouTube and Odyssey. I would also update the instructions here: [https://wiki.opensourceecology.org/wiki/Generating\_G\_Code\_for\_the\_D3D\_Universal\_Plotter\_with\_Open\_Source\_Software](https://wiki.opensourceecology.org/wiki/Generating_G_Code_for_the_D3D_Universal_Plotter_with_Open_Source_Software)&quot;

6.    Was FreeCAD hard to learn? What did you think of the resources/tutorials available to you?
&quot;For me, I struggled a little learning FreeCAD. I do think the resources available are great and helped a lot, but I didn&#39;t learn them in the time span they aim for. I look forward to using it more in future projects though.&quot;

7.    Do you have in person meetings with other developers?
&quot;No&quot;

8.    Favorite machine/project you&#39;ve worked on at OSE and why?
&quot;I&#39;ve so far only worked on the Documenting Pen Plotter Flows project.&quot;

9.    Can you explain what Factor E Farm is? Do all the developers build/work there? Do you work there?
&quot;Factor E Farm is kind of the flagship hackerspace associated with this project. It&#39;s in Kansas. No, not all developers build/work there. I don&#39;t work there. I do want to visit eventually. [https://wiki.opensourceecology.org/wiki/Factor\_e\_Farm](https://wiki.opensourceecology.org/wiki/Factor_e_Farm) &quot;

10. Other ways of communicating with others in the team besides the wiki?
&quot;Primarily the wiki, but also email. There is something I call the &quot;fan discord&quot; which is unofficial. There is also a kind of deadish Slack which I also think is unofficial. Slack and Discord aren&#39;t open source for one thing. Theoretically there would be meetings from time to time but I think we don&#39;t have enough people, perhaps.&quot;

11. What was the interview process like? What knowledge/experience are you expected to have?
&quot;I did a video interview per [https://wiki.opensourceecology.org/wiki/Volunteer\_Application](https://wiki.opensourceecology.org/wiki/Volunteer_Application)
 This was my video: [https://www.youtube.com/watch?v=hMkiCVaUXDg](https://www.youtube.com/watch?v=hMkiCVaUXDg)
Marcin replied to let me know I should embark on the Developer Test.
[https://wiki.opensourceecology.org/wiki/Developer\_Test](https://wiki.opensourceecology.org/wiki/Developer_Test)
I managed to pass just enough to start work. &quot;

12. What is it like working with your team members?
&quot;I only worked with Marcin. It was difficult working remotely, but overall he was very responsive. &quot;

13.  Have you used any of the blueprints made by OSE yourself?
&quot;I have not tried to make anything in the official project, but I am trying to make Dirk&#39;s 3D printed motor. I am stuck at the copper coil step, though.&quot;

14. How is the organization structured? Is there a team leader you report to?
&quot;I report directly to Marcin.
You&#39;ll notice there are stars, I guess that&#39;s kind of an organization. I&#39;m technically a one star dev, but I opted to not move myself over until I successfully finish my project, which was held up right at the end by a problem I couldn&#39;t quite figure out at the time.
[https://wiki.opensourceecology.org/wiki/Development\_Team\_Log](https://wiki.opensourceecology.org/wiki/Development_Team_Log)
As you can see, we still don&#39;t have that many active collaborators. Although 20 are listed (including myself, who is barely active), you&#39;ll notice for example that only 6 people logged work for March. &quot;