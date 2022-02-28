## How to use the OSPO Guide

There has been an OSPO terminology misalignment caused by The Open Source Program Office expansion over the past years across sectors and regions. 
The OSPO guide is an ongoing set of documents that provides a holistic view and alignment of Open Source Program Office terminology, tasks, 
and responsibilities, as well as public use cases and learning resources in a cohesive application.

### Contributing to this guide

The OSPO Guide works using a markdown file called `guide.md`. If you would like to contribute, please open at PR in the [OSPO Landscape Repo](https://github.com/todogroup/ospolandscape).

## How to use the OSPO Landscape

The OSPO landscape is intended as a map to explore the OSPO Ecosystem in terms of tooling, adopters and involved communities. It also shows current TODO members.
It is modelled after the Cloud Native Computing Foundation (CNCF) landscape and based on the same open source code.

### OSPO Adopters

Organizations who has a public OSPO or similar initiative that meets OSPO Definition requirements
  
### OSPO Tools

A set of packages and projects packages and projects that are helpful for managing open source projects and offices
OSPO Associates
Communities or projects that work closely with OSPOs orhelp the OSPO Movement with valuable resources and contributions. OSPO Associates work in collaboration with the TODO Community.

### TODO Member

Organizations that are members of the TODO Group

### Adding Resources 

If you think your project should be included, please open a pull request to add it to landscape.yml. For the logo, you can either upload an SVG to the hosted_logos directory or put a URL as the value, and it will be fetched.
Netlify will generate a staging server for you to preview your updates. Please check that the logo and information appear correctly and then add LGTM to the pull request confirming your review and requesting a merge.

> Not sure how to start? Email ana@todogroup.org for advice

## OSPO Glossary

### OSPO Definition 

An open source program office (OSPO) is a designated place that acts center of competency for an organization's open source operations and structure. This can include setting code use, distribution, 
selection, auditing and other policies, as well as training developers, ensuring legal compliance and promoting and building community engagement that benefits the organization strategically.
We can categorize the functions of a typical OSPO into three categories: Legal Risk Mitigation, Improving Engineers’ Practices, and Enabling Financial Benefits. (A mnemonic: Fear, Love, and Money).

If an organization invests in a place or team to manage open source operations and structure, then it can be considered an OSPO. However, OSPOs might use different naming depending on the organization
and how advanced the program is. Some OSPO variants include:

* The Open Source Steering Committee
* Community Development team
* Open Source Software Operations
* Open Source Board
* Open Source Office

> ##### INFOBOX
> For better alignment, it is recommended to use the word OSPO or Open Source Program Office and avoid OSPO Variants as much as possible.
> 
> * [OSPO Definition](https://github.com/todogroup/ospodefinition.org)

### OSPO Tools

A set of packages and projects packages and projects that are helpful for managing open source projects and offices

> ##### INFOBOX
> * [Awesome OSS Management](https://github.com/todogroup/awesome-ospo)
> * [OSPO Metrics Tools / Services](https://github.com/todogroup/awesome-ospo)

#### Source Code Review

Source code review is the examination of an application source code to find errors overlooked in the initial development phase. 
A tester launches a code analyzer that scans line-by-line the code of an application. The code review process also referred to as peer review, stands out 
as a tried and tested method in a large palette of applications to allow for the systematic examination of software source code. It's conducted to find bugs and improve the overall quality of the software

* [mention-bot](https://github.com/facebookarchive/mention-bot) - The mention bot will automatically mention potential reviewers on pull requests. It helps getting faster turnaround on pull requests by involving the right people early on.
* [PullApprove](https://www.pullapprove.com) - Allows for fancier rules on how pull requests are approved.
* [sentinel](https://github.com/habitat-sh/sentinel) - PR Test, review, and merge workflow bot
* [pull-review](https://github.com/imsky/pull-review) - assign pull request reviewers intelligently, inspired by mention-bot
* [pull-request-size](https://github.com/noqcks/pull-request-size) - Automatically adds GitHub labels based on the size of a Pull Request.
* [Pullie](https://github.com/godaddy/pullie) - GitHub App that helps with PRs: requests reviews, links Jira tickets, nags for missing required file changes (e.g. changelog entries)

> ##### INFOBOX
> * [Code Review Tools](https://github.com/todogroup/awesome-ospo#code-reviews)


#### Continuous Integration (CI) / Continuous Deployment (CD) 

CI/CD is a method to frequently deliver apps by introducing automation into the stages of app development. The main concepts attributed to CI/CD are continuous integration, continuous delivery, and continuous deployment. 
CI/CD is a solution to the problems integrating new code can cause for development and operations teams. CI/CD tools can help to automate development, deployment, and testing. 


* [GitHub Actions](https://github.com/features/actions) - Automate your workflow from idea to production.
* [Jenkins](https://www.jenkins.io/) - open source automation server that provides hundreds of plugins to support building, deploying and automating any project.
* [Jenkins X](https://jenkins-x.io/) - open source CI/CD solution for modern cloud applications on Kubernetes.
* [Ortelius](https://ortelius.io/) - providing a central catalog of services with their deployment specs, application teams can easily consume and deploy services across cluster.
* [Screwdriver](https://screwdriver.cd/) - Screwdriver is an open source build platform designed for Continuous Delivery.
* [Spinnaker](https://spinnaker.io/) - multi-cloud continuous delivery platform for releasing software changes with high velocity and confidence
* [Tekton](https://tekton.dev/) - set of shared, open source components for building CI/CD systems
* [Travis CI](https://travis-ci.org/) - A hosted continuous integration service used to build and test software projects hosted at GitHub and Bitbucket


> ##### INFOBOX
> * [CI/CD Tools](https://github.com/todogroup/awesome-ospo#continuous-integration--continuous-delivery) 

#### CLA (Contributor License Agreements) 

The agreement between the contributor and the project which gives the project additional rights on top of the rights given 
by the license. If people contribute on behalf of a company, where the company holds the rights on the work of the contributor, the company has to sign the CLA. 

There is a variety of different CLAs in use, some mostly confirm the rights already given by the license, some give additional rights such as being able to 
release the code under a different license, for example when the code is also released under a proprietary license as part of a commercial offering. With CLA, rights are collected at a central place, so changing the license, or rereleasing the code as part of a product with a different license is possible. The asymmetry of the agreement, which gives the project more rights than its contributors can impose a bigger barrier for contributions. Requiring a corporate CLA can also be an insurmountable barrier, especially for large corporations, because the effort and legal implications of checking and signing a CLA might outweigh the benefits of contributing.


* [CLA Assistant](https://github.com/cla-assistant/cla-assistant) - Streamline your workflow and let CLA assistant handle the legal side of contributions to a repository for you. CLA assistant enables contributors to sign CLAs from within a pull request.
* [CLA Portal](https://github.com/vmware/claportal) - Enables a workflow for contributors to sign a CLA for pull requests to your GitHub repositories. Also supports DCO sign-offs in the commits.
* [OSS Contribution Tracker](https://github.com/amzn/oss-contribution-tracker) - Track contributions made to external projects and manage CLAs
* [Dr CLA](https://github.com/salesforce/dr-cla) - GitHub bot for dealing with Contributor License Agreements

> ##### INFOBOX
> * [What is CLA](https://yahoo.github.io/oss-guide/docs/resources/what-is-cla.html)
> * [CLA Tools](https://github.com/todogroup/awesome-ospo#contributor-license-agreements--developer-certificate-of-origins)

#### Developer Certificate of Origin (DCO): 

The DCO was introduced in Linux kernel development and has been adopted by quite some other projects. It's a statement developers give with each commit 
by including a "Signed-Off-By" statement in the commit message. With this statement developers explicitly declare that they have the rights they need to do 
the contribution and that they agree that the project is using it. This is still a low barrier, but it gives projects more security about if code was rightfully 
contributed. It does not help in cases where the license of the code needs to be changed.

* [DCOB](https://github.com/chef/dcob) - A bot for enforcing developer certificate of origin sign-offs for each commit in a PR
* [DCO Bot](https://github.com/probot/dco) - GitHub App that enforces the Developer Certificate of Origin (DCO) on Pull Requests

> ##### INFOBOX
> * [DCO Tools](https://github.com/todogroup/awesome-ospo#contributor-license-agreements--developer-certificate-of-origins)

#### SCA (Software Composition Analysis)

An automated process that identifies the open source software in a codebase. The analysis is performed to evaluate security, license compliance, and code quality. 
SCA tools should enable developer teams to embrace security throughout the SDLC (Software Development Cycle).

> ##### INFOBOX
> * [OSPO SCA Tools](https://landscape.todogroup.org/card-mode?category=sca&grouping=category)

#### Project Quality

Composed by standards, best practices, tools, and framework to assess project quality.

* [CII Best Practices Badging](https://bestpractices.coreinfrastructure.org/) - The Core Infrastructure Initiative (CII) Best Practices badge is a way for Free/Libre and Open Source Software (FLOSS) projects to show that they follow best practices. Projects can voluntarily self-certify, at no cost, by using this web application to explain how they follow each best practice.
* [Fosstars](https://github.com/SAP/fosstars-rating-core) - A framework for defining and calculating ratings for open source projects
* [RepoLinter](https://github.com/todogroup/repolinter) - Lint open source repositories for common issues.
* [RepoLinter Dashboard](https://github.com/todogroup/repolinter-dashboard) - A Dashboard for RepoLinter
* [Linguist](https://github.com/github/linguist) - Identify the programming languages used in a project.
* [repo-scaffolding](https://github.com/twitter/repo-scaffolding) - Scaffolding tools for creating and maintaining projects based on Twitter Open Source standards and best practices.
* [Repo Health Check](https://github.com/dogweather/repo-health-check) - Analyze a project: How are the maintainers doing?

> ##### INFOBOX
> * [OSPO Project Quality Tools](https://landscape.todogroup.org/card-mode?category=project-quality&grouping=category)
> * [OSPO Project Quality Category](https://github.com/todogroup/awesome-ospo#project-quality)

#### Supply Chain Trust 

* [OpenChain Conformance](https://certification.openchainproject.org) - The OpenChain Specification is a way for companies using Free/Libre and Open Source Software (FLOSS) to show that 
they meet the key requirements for quality compliance programs. Companies can voluntarily self-certify, at no cost, by using this web application.

> ##### INFOBOX
> * [OSPO Supply Chain Trust Tools](https://github.com/todogroup/awesome-ospo#supply-chain-trust)

#### Licencing 

An Open Source License is a legal document that defines the terms under which permission is granted by a rights holder to the recipient. 
Open source licenses [listed here](https://opensource.org/licenses) allow software to be used, modified, and shared by anyone for any purpose with very few restrictions.

* [SPDX](https://spdx.org) - Set of standards for communicating the components, licenses and copyright associated with a software package.
* [LicenseFinder](https://github.com/pivotal-legacy/LicenseFinder) - Find licenses for your project's dependencies
* [ScanCode toolkit](https://github.com/nexB/scancode-toolkit) - Scan code for licenses, copyright and dependencies
* [FOSSology](https://www.fossology.org) - Scan code for license, copyright and export control information
* [Licensee](https://github.com/benbalter/licensee) - Identify a project's license file
* [License Identifier (LiD)](https://github.com/codeauroraforum/lid) - Identify and extract license text from source code
* [askalono](https://github.com/amzn/askalono) - a library and command-line tool to help detect license texts. It's designed to be fast, accurate, and to support a wide variety of license texts.
* [License Classifier](https://github.com/google/licenseclassifier) - A library and set of tools that can analyze text to determine what type of license it contains
* [OSS Attribution Builder](https://github.com/amzn/oss-attribution-builder) - The OSS Attribution Builder is a website that helps teams create attribution documents (notices, "open source screens", credits, etc) commonly found in software products.
* [OSS Review Toolkit](https://github.com/heremaps/oss-review-toolkit) - enables highly automated and customizable Open Source compliance checks od the source code and dependencies of a project by scanning it, downloading its sources, reporting any errors and violations against user-defined rules, and by creating third-party attribution documentation.
* [fossa-cli](https://github.com/fossas/fossa-cli) - Fast, portable and reliable dependency analysis for any codebase
* [Licensed](https://github.com/github/licensed) - A Ruby gem to cache and verify the licenses of dependencies
* [LicensePlist](https://github.com/mono0926/LicensePlist) - A command-line tool that automatically generates a Plist of all your dependencies, including files added manually(specified by YAML config file) or using Carthage or CocoaPods.
* [dpkg-licenses](https://github.com/daald/dpkg-licenses) - A command line tool which lists the licenses of all installed packages in a Debian-based system (like Ubuntu).
* [FOSSID](https://fossid.com) - A comprehensive commercial scanner for licenses and vulnerabilities. Knowledgebase covers 78M+ repositories and 600B+ snippets. Includes detailed snippet scanning to detect the license on fragments and copied/pasted code, even if the open source license is not explicitly or correctly declared.
* [DependencyTrack](https://github.com/DependencyTrack/dependency-track) - Dependency-Track is an intelligent Component Analysis platform that allows organizations to identify and reduce risk in the software supply chain ScanOSS - Scan your codebase for snippets and plagerism from large knowledge base of open source projects. Designed to integrate with CI/CD and modern IDEs, to "start left" to do continuous validation instead of one report at the end. Product itself is fully open source.
* ScanOSS - Scan your codebase for snippets and plagerism from large knowledge base of open source projects. Designed to integrate with CI/CD and modern IDEs, to "start left" to do continuous validation instead of one report at the end. Product itself is fully open source.

> ##### INFOBOX
> * [Yahoo’s open source licensing guide](https://yahoo.github.io/oss-guide/docs/resources/license.html)
> * [Licencing Tools](https://github.com/todogroup/awesome-ospo#licensing)



#### Project Documentation

* [Docusaurus](https://docusaurus.io) - Docusaurus is a React-based static site generator, specifically developed to more easily help create and maintain open source websites.
* [GatsbyJS](https://www.gatsbyjs.org/) - Gatsby is a site generator that allows you to build fast websites and apps with React.
* [VuePress](https://vuepress.vuejs.org/) - VuePress is a minimalistic Vue-based static site generator, optimized for writing technical documentation.

#### Security

* [Eclipse Steady](https://github.com/eclipse/steady) - Eclipse Steady, formerly known as "Vulnerability Assessement Tool" (Vulas), helps to discover, assess and mitigate known vulnerabilities in Java and Python projects.

### Open Source Manifesto

A document that details core values, company principles and employee principles when engaging in open source.

> ##### INFOBOX
> * [Mercedes FOSS Manifesto](https://opensource.mercedes-benz.com/news/the-Mercedes-Benz-foss-manifesto)

### Open Source Strategy Document

An internal document that details an organization’s open source strategy in a format that everyone from engineering and legal, to marketing and the C-suite can reference. This strategy document helps teams across divisions understand the business objectives behind your open source program, ensure better decision-making, and minimize risks.

> ##### INFOBOX
> * How to Set an Open Source Strategy
> * Open Source Guide by Yahoo

### Software Bill of Materials

A nested inventory for software, a list of ingredients that make up software components. 


> ##### INFOBOX
> * [SBOM by NTIA](https://www.ntia.gov/sbom) 

## OSPO Five-Stage Maturity Model

A set of patterns and directions as well as a checklist, to help implement an OSPO or an open source initiative within corporate environments. People can read and download the full whitepaper [here](https://linuxfoundation.org/tools/the-evolution-of-the-open-source-program-office-ospo/)

![OSPO Maturity Model](https://landscape.todogroup.org/images/LFResearch_OSPO_Report_Fig2.jpg)


### Stage 0: Adopting Open Source Ad Hoc

Today, almost all organizations use OSS. How they adopt and initially use it varies. They may use OSS  as a building block or library in a product or tool or a key part of a vendor’s product stack or supporting the vendor’s service offering. Developers may use OSS for rapid prototyping or for microservices and small applications. Developers also frequently adopt OSS development tools such as integrated development environments (IDEs), or tools built on top of open source like GitHub and GitLab. Modern cloud native applications, almost by default, use open source systems for container orchestration, observability, data storage, messaging, and more. On the front-end of applications, developers rely heavily on open source libraries and frameworks.

Red Hat reported that “90% of IT leaders are using enterprise open source.” Software composition analysis vendors like Synopsys determined that over 75% of all codebases contained open source components.
In other words, nearly every organization is using open source. However, the very earliest form of adoption is ad hoc, by developers solving problems using readily available tools and technologies. This “ad hoc adoption” usually means little thought is given to license compliance outside the defaults or to longer-term impacts of consuming open source and distributing products built with open source components. In most of these instances, a few engineers are actively seeking out open source while the rest of the engineering organization may use open source coincidentally but does not view its activities as dependent on open source. Consequently, the organization has neither a centralized team focused on open source nor a top-level open source strategy for the organization. These are critical because, once adopted, those open source components become part of the organization software supply chain by default, which makes a strategic approach all the more imperative.

### Stage 1: Providing OSS Compliance, Inventory, and Developer Education

In general, an organization forms an OSPO when it realizes that its people are consuming open source products and code across nearly all engineering and development departments and functions. This usage is typically internal, not part of products or services to customers or users. In reality, any organization with a considerable IT function and an advanced online or application-centric presence uses open source, because of the ubiquity of open source throughout the technology stack—from Linux servers and MySQL databases to programming languages like NodeJS and Python and front-end frameworks like React and Vue.js.
At this early stage, organizations often use many different names for the OSPO. IBM initially called its programmatic open source efforts the “Open Source Steering Committee,” for example. In all cases, however, organizations in Stage 1 recognize that OSS is a key part of their business and technology strategy. They understand that the security practices of OSS projects differ from those of proprietary software companies. For example, disclosure rules of OSS projects tend to be stricter than those of proprietary projects. So they must identify their legal and security risks. Risk mitigation strategies include careful licensing, developer education, and rigorous inventory-taking.


**Managing Legal Risks and Licenses**
An organization’s legal team or technology leaders tend to launch Stage 1 development of an OSPO to ensure that its employees (and contractors, suppliers, etc.) all use OSS according to its license terms and that the organization’s OSS consumption is not putting it at legal risk. There are dozens of OSS licenses in use. In the 2020 survey, respondents ranked compliance as the top benefit of OSPOs of larger companies, and compliance remains the second leading benefit for medium-sized companies. “Companies usually start out with a lot of confusion. There are no policies for license compliance in place, and developers do what they feel is right,” said Dirk Riehle, professor of open source software at the Friedrich-Alexander University Erlangen-Nürnberg. He added:

> I once walked into a company, and one developer said: We have no open source policy. Another quipped: We do, and it is: No open source. To which a third commented with a frowning face: ‘What are you talking about? We have been contributing to open source projects for a while now.’ This is not unusual. They will eventually set-up an open source program office with the mandate to get a handle on open source use and contribution.

While OSS users have always considered legal compliance, some OSS contributors have designed new licenses to discourage large cloud providers from creating proprietary services based on open source projects. The most prominent of these is the Affero General Public License (AGPL). A company might use OSS released under the terms of this license to deliver proprietary software-as-a-service (SaaS) to its customers, but the creator of the OSS might have grounds to sue the company for license violation if the AGPL terms do not clearly distinguish between internal and external delivery. Many businesses also have internal financial charging systems between units, further blurring the line between a paid service and an internal service. 

**Educating Developers**

To maintain compliance, organizations in Stage 1 of OSPO maturity create education programs to help their developers decide when to use OSS in creating new products or services. “Many developers who are not educated in open source think that because they are not purchasing software, there is no license involved because they didn’t sign a contract,” said Suzanne Ambiel, director of open source marketing and strategy at VMware. “Open source software may be free—as in priceless—it can also be costly if used in a noncompliant way. [OSS] always comes with a license. One of the most important roles of any OSPO is to make sure developers understand the implications of different license choices.”
Through developer education, senior management often acknowledges the value and importance of OSS. In such programs, developers learn:

* The nuances of different license types
* The formal approval processes for introducing new OSS products 
* The real risks of noncompliant OSS consumption, including the usage of OSS products from projects or code without formal licenses
* The use of contributor license agreements (CLAs) to cover an organization’s developers who contribute to open source

Sometimes the organization introduces a formal CLA policy at this stage. It may also provide guidance on judging the health of OSS projects as part of its criteria for deciding which OSS to use in the organization’s technology stack or infrastructure. 

**Taking Software Inventory**

Developers may deploy OSS ad hoc without cataloging their efforts systematically. The legal team and technology leadership tend to push for an inventory of all OSS in use in an organization. Such an inventory itemizes OSS in organization’s code repositories (e.g., GitHub, GitLab) and systems. Stage 1 organizations set up specific software inventory processes to create an organization-wide software bill of materials (SBOM). With this inventory, the legal team—usually working with the OSPO team—can continuously monitor OSS usage and flag legal, security, or other project risks. With a detailed SBOM, technology leadership such as a chief technology officer (CTO) or chief information officer (CIO) can identify and closely monitor the most business-critical uses and preserve organizational security.

### Stage 2: Evangelizing OSS Use and Ecosystem Participation

After organizations recognize the value of OSS and the need for compliance, education, and an SBOM, they begin to realize the economic benefits of OSS usage and seek to expand it. OSPOs in Stage 2 create such internal mechanisms as ambassadors who promote usage of approved OSS products, educational programs on good OSS hygiene, and technical training or tuition reimbursement for skill building and certification in OSS. With these initiatives, an organization can grow its use of OSS and amplify its message that OSS is not only important but desirable and preferable to proprietary software products. 
Employee education includes laying out best practices in interacting with OSS projects such as how to request features, file bug reports, and contribute basic code. During this stage, the organization strengthens its collaborative muscle and experiences the social life of an OSS project and community. At this point, the OSPO communicates to employees and managers the importance of contributing to and not merely consuming OSS. This outreach includes advocating for and driving event sponsorships, booking project leads and maintainers as speakers or panelists in public coding forums, and securing organizational resources (e.g., talent, funding) to mission-critical OSS projects.

For organizations, active and visible participation yields multiple benefits: better visibility, better reputation, more attractive employer. To this end, many non-tech organizations purchase booths at prominent OSS events to interact more with those communities and recruit developers who enjoy working in OSS ecosystems. Technology companies active in open source may extend education programs to customers who want to interact with OSS communities and vendors. “We get so many requests from our customers asking for help and guidance on how to participate in open source or how to contribute or collaborate with us on projects,” said Deborah Bryant, senior director of open source at Red Hat.

As they advance in Stage 2, organizations begin incentivizing their developers to work on OSS projects critical to their operations, to the degree that developers become highly active contributors or primary maintainers. To technology organizations, employing a contributor to a prominent OSS project is a valuable investment: most of their contributors to, say, the Linux kernel—the core component of the Linux operating system and the critical interface between computer hardware and software—are full-time employees (FTEs) whose job is to write code for Linux. 

Outside the technology sector, fewer organizations can assign FTEs to open source work, but they are doing it. For example, both Comcast and Bloomberg have employees working full-time on OSS projects. In this stage of the life cycle, OSPOs begin exploring how to streamline processes for developers to consume OSS. Such developer efficiency may include simplifying CLAs, adding OSS with acceptable license types to ticketing systems for fast approval, promoting reuse of OSS architecture and software in place (a variation on inner-sourcing), and standardizing library selection and open source development tools, thereby blending OSPO and platform operations duties.

At this stage, organizations turn to OSPOs for guidance on how to engage positively with open ecosystems. “You have to make sure that you give back just as much as you take in. You don’t want people to think you are just monetizing open source without contributing back to the community,” said Chris Xie, head of the OSPO at Futurewei Technologies. “We take that strongly into account—more strongly than ever.” Companies in regulated sectors like telecommunications must also understand their national export laws and navigate political tensions to preserve the OSS community and steer clear of international entanglements. “We always want to make sure our contributions are truly open, benefiting the community, and benefitting the industry at large,” Xie explained.

Usually in Stage 2 of the OSPO maturity cycle (or sometimes in Stage 1, if the company is a software or core technology company), OSPOs begin to streamline and optimize open outbound source contributions for their developers. The process of requesting and getting approval for outbound participation is usually ad hoc and painful in the early days. “One of the first things we looked at when we established the OSPO was the process for contributions,” said Michael Picht, chief architect of the OSPO at SAP. “Using Word, Excel, and email, the process was not automated at all. When we opened the OSPO, one of the first things we did was simplify the process and implement end-to-end tool support. We use GitHub issues for the different process steps.”

### Stage 3: Hosting OSS Projects and Growing Communities

At Stage 3, organizations initiate and then host or act as primary sponsors of OSS projects. They will dedicate one or more FTEs to a project, and they accept responsibility for nurturing a project community and ensuring its health. They don’t confuse this level of organizational commitment with individual employees who decide to open-source their projects. In Stage 3, organizational leaders support incubating and launching open source projects into the public sphere because they understand how these projects benefit their organization. Such projects tend to offer better performance and economics on crucial capabilities that may be noncore to the organization’s value proposition but critical to its technology infrastructure. 

In addition, organizations that create and launch open source projects establish broad credibility in the open source community; the possibility of working on open source technology is attractive to many developers. Most of the OSPOs we spoke with cited recruitment of new engineering talent and retention of existing talent as a key motivation of the open source effort.

In a recent study by the Linux Foundation Research of the financial services industry, 53% of contributors said they contributed to OSS because “it’s fun.”
Supporting a project with FTEs and funding is true skin in the open source game. Organizations that cross this threshold and successfully launch multiple open source projects develop internal resources and processes that can incubate and ensure the success of these projects post launch. OSPOs are more than just gatekeepers and mentors for project formation and launch; they educate project creators on the requirements for cultivating a healthy open source ecosystem, and they coach project leads to prepare them for a more public leadership role required of an OSS project. 
As an OSS organization matures, its OSPO develops internal processes, playbooks, checklists, tooling, and other mechanisms to vet, organize, and operate open source projects and to prepare and coach their leaders. Some OSPOs prefer to launch projects with the assistance of the major open source foundations or collaboratives such as the TODO Group to enhance capabilities or provide infrastructure, tactical assistance, and other resources. This preference is less resource intensive but cedes control of a project to a broader community.

### Stage 4: Becoming a Strategic Decision-Making Partner

At this maturity stage, the OSPO becomes a strategic partner for technology decisions, helping to guide choices and shape long-term commitments to projects. At Stage 4, the CTO and other technology leaders consult the OSPO and its leadership on which open source technologies to rely on and which decision criteria to use in judging open source projects. Because major open source technology choices tend to generate significant secondary and tertiary costs and affect upstream and downstream technologies as well as hiring plans, the choice of open source projects becomes a major business decision. 
In broad terms, OSPOs provide three types of strategic guidance in Stage 4. First, the OSPO advises the CTO and technology leadership on which open source technologies to adopt or remove from the organization’s technology stack. Given the many OSS options today—with most major categories of software featuring dozens of choices as shown in Figure 2—the OSPO can provide insights into OSS trends such as popularity of different languages, designs of APIs, or capabilities of different NoSQL databases. In this role, the OSPO becomes an internal technology consultant to the CTO and the in-house expert on OSS. 

In a second type of strategic guidance, OSPOs take the lead on benchmarking what constitutes an acceptable OSS project. The OSPO often evaluates the behavior and performance of the project, especially changes in license type that limit usage, or abrupt shifts in the project roadmap, to determine whether a project manager has the best interests of the community in mind. Most OSPOs rely on back-of-the-envelope metrics to evaluate project behavior such as:

* Which type of license does it have?
* What is its code of conduct, and what are the consequences for breaking it?
* What is its governance structure, and does this structure ensure independence?
* How long does it take to respond to pull requests or bug filings?
* How frequently does the project ship new versions?
* Does one party (company or organization) or a whole community control the project?
* How many contributors does the project have? How has that number changed over time?

A third type of guidance is helping organizations understand and navigate project politics, such as maintaining a neutral stance when multiple influential actors are attempting to steer a project, or illuminating the latent political considerations of community members. At a higher plane, OSPOs can help companies maintain a neutral posture on techno-nationalism and bridge political differences by cultivating personal and working relationships that transcend national boundaries and political realms. Increasingly, this value extends to the work of foundations and nonprofits, as those realms become important neutral spaces in open source.
According to Deborah Bryant of Red Hat, her OSPO has had to manage the cost of participating in open source foundation work, between sponsoring and dedicating staff to fill leadership roles. “We have found that we have needed to spend more time on some central management and administration of our participation in software foundations to ensure that we were getting a return on our investment and to re-evaluate our participation on a regular cadence,” she said. 
In this role, where the OSPO has a multimillion-dollar foundation budget, the strategic importance of participating in OSS ecosystem formation and growth parallels the monetary investment in foundations and nonprofits. During this stage, we tend to see rapid growth in the OSPO. According to Ambiel of VMware:

> One of the OSPO’s primary goals today is to help with best practices in coaching and how to be a good open source citizen. When you are in the open source community, you are participating in the open—everyone can see what you are doing. It’s important that an organization brings its best. The OSPO helps people do that consistently and confidently, be it for speaking at a conference or contributing a small library to participating in a big project community such as Kubernetes.

> ##### INFOBOX
> [Leveraging the Open Source Program Office: New Research Unpacks the Evolution of the OSPO (and a Whole Lot More)](https://linuxfoundation.org/blog/leveraging-the-open-source-program-office-new-research-unpacks-the-evolution-of-the-ospo-and-a-whole-lot-more/)
> [The Evolution of the Open Source Program Office (OSPO)](https://linuxfoundation.org/tools/the-evolution-of-the-open-source-program-office-ospo/)


## OSPO Categories & Responsibilities

OSPO functions can be structured into three categories: Legal Risk Mitigation, Improving Engineers’ Practices and Enabling Financial Benefits.

### Legal Risk Mitigation

Often, the first concern companies have is related to legal compliance. OSPOs often oversee aspects of a company’s open source license compliance process. Companies that distribute software are typically most concerned with this and initiate their OPSO around the abatement of legal risk. The responsibilities of a program office in this area includes:

* Maintaining open source license compliance reviews and oversight
* Running a review process for inbound code use
* Ensuring that the company contributes back to open source projects effectively



### Improving Engineers’ Practices 

OSPOs also improve engineering capabilities by providing guidance and policies about code management in an open source (and blended source) environment. 
Companies with many software engineers focus their OSPO on engineering policies and practices. The responsibilities of a program office in this area include:

* Clearly communicating the open source strategy within and outside the company
* Fostering an open source culture within an organization
* Ensuring high-quality and frequent releases of code to open source communities

### Enabling Financial Benefits 

Some companies focus on the financial implications of open source and leverage their OSPO to help drive a strategy around the use of commercial vs. open source vendors. Whereas some tech companies use their OPSO (and open source projects) to drive customers to commercial products. The responsibilities of a program office in this area includes:
Owning and overseeing the execution of the strategy.

* Facilitating the effective use of open source in commercial products and services
* Engaging with developer communities to encourage adoption of strategic open source projects

> Each open source program office is custom-configured based on its particular business, products, and goals.


## OSPO Career Path

Job Examples

The following [list](https://github.com/todogroup/job-descriptions) provides published job descriptions related to open source program office (OSPO) roles. 
Use these examples to inform you when creating of a job description of your own and to get a sense of the types of roles found in OSPOs. 

Some of the examples include:

* Head of OSPO
* Software Architect
* Technical Evangelist
* Compliance Engineer
* Legal Counsel


>##### INFOBOX
>[OSPO Job Descriptions](https://github.com/todogroup/job-descriptions)

## OSPOs In Practice

#### Autodesk
The history of Autodesk’s open source transformation began shortly after the shift of all its products to cloud began, including its AutoCAD architecture software, 
building information modeling with its Revit products, as well as its media and entertainment products. [Learn more about Autodesk’s OSPO case study](https://todogroup.org/guides/casestudies/autodesk/).
#### Comcast
Comcast ’s involvement in open source was a gradual process that evolved over time. The company eventually created two open source program offices, 
one for the NBC business and another for the cable side of the business, which is the subject of this profile. Learn more about [Comcast OSPO case study](https://todogroup.org/guides/casestudies/comcast/).
#### Dropbox
The open source program at Dropbox was initially just a mailing list, where some interested engineers wanted to open source projects and develop with open source. 
Over time, things became more formalized, with a focus on ensuring that the company was consistent about what code it would release versus what code was best 
kept internal. Learn more about [Dropbox case study](https://todogroup.org/guides/casestudies/dropbox/).
#### Meta
Meta has a dedicated Tools team within the open source program office that is responsible for building internal tools to help manage its open source portfolio. 
This includes the projects that Meta shares, which are mostly hosted on GitHub, as well as the other external projects they contribute to such as the Linux Kernel. 
Learn more about [Meta’s case study](https://todogroup.org/guides/casestudies/facebook/).
#### Microsoft
Microsoft does not have a central open source strategy or a central approval body. Instead, the Open Source Programs Office facilitates those discussions and 
decisions throughout the company. Teams still need to have their open source engagement reviewed, but it is done more locally. Learn more about [Microsoft’s 
case study](https://todogroup.org/guides/casestudies/microsoft/).
#### National Instruments
From shipping its first real-time Linux device that initiated a steady stream of open source involvement across multiple company products and organizations 
to establish an open source “guild” to increase open source awarenes. Learn more about [National Instrument’s case study](https://todogroup.org/guides/casestudies/ni/).
#### Red Hat
The open source and standards office at Red Hat (or what some would refer to as an open source program office) was established years ago to create a consistent way 
to support communities and open source technologies from companies we acquired from time to time. Red Hat created a centralized organization of expertise to 
support the rest of the company in achieving its goals through open source. Learn more about [Red Hat case study](https://todogroup.org/guides/casestudies/redhat/).
#### Salesforce
Salesforce has many priorities around open source. The company’s open source strategy keeps everyone aligned. The dedicated open source program team circulates internal documents to the company’s engineering team that provide strategic guidance and encourage the creation and use of open source. The documents provide the foundation for an open source culture and let the team know in no uncertain terms that the company’s leaders are fully behind the strategy. Learn more about Salesforce case study.

#### SAP
SAP has been working with open source for decades and has now established an open source program office (OSPO) to further formalize the coordination of its open source activities 
and expand its engagement with the open source communities. Learn more about [SAP case study](https://todogroup.org/guides/casestudies/sap/).

#### Uber
Uber is one of the best-known disruptors in the digital age. Its business model famously separated transportation services from the traditional underlying 
infrastructure with an app-based model offering on-demand and multimodal options. In many ways, this transformation, and Uber itself, also mirror the creative and 
collaborative aspects of the open source community. Learn more about [Uber case study](https://todogroup.org/guides/casestudies/uber/).

### Traditional & regulated environments

#### Alliander (Energy)
Learn more about [Alliander’s OSPO case study](https://youtu.be/WjJUXfqaFCw)
#### Capital One (Banking)
The Open Source Office at Capital One adopted a comprehensive risk management approach wherein we have identified clear risk ownership around when to use, 
contribute to, and launch open source projects. Learn more about [Capital one case study](https://todogroup.org/guides/casestudies/capitalone/).
#### RIT (Academics)
Open@RIT is dedicated to fostering an “Open Across The University” collaborative engine for Faculty, Staff, and Students. Its goals are to discover and grow 
the footprint, of RIT’s impact on all things Open including, but not limited to, Open Source Software, Open Data, Open Science, Open Hardware, Open
Educational Resources, and Creative Commons licensed efforts; what we like to refer to in aggregate as Open Work. Learn more about [RIT case study](https://todogroup.org/guides/casestudies/rit/).


## OSPO Learning

### The OSPO Hub

Are you a student / graduate willing to start an OSPO career path or an Open Source Proffesional thinking about specializing in OSPO? Discover OSPO resources and initiatives to
learn about OSPOs and advance in your OSPO career. The [OSPO Hub](https://github.com/todogroup) is a collaborative space under CC-BY 4.0 Licence that contains:

* OSPO Training Modules
* OSPO Meetings
* OSPO Events
* OSPO Studies

And more!






