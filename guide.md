## How to use the OSPO Guide

There has been an OSPO terminology misalignment caused by The Open Source Program Office expansion over the past years across sectors and regions. 
The OSPO guide is an ongoing set of documents that provides a holistic view and alignment of Open Source Program Office terminology, tasks, 
and responsibilities, as well as public use cases and learning resources in a cohesive application.

## How to use the OSPO Landscape

The OSPO landscape is intended as a map to explore the OSPO Ecosystem in terms of tooling, adopters and involved communities. It also shows current TODO members.
It is modelled after the Cloud Native Computing Foundation (CNCF) landscape and based on the same open source code.

### OTODO Members

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

> Not sure how to start? Email ana@togroup.org for advice

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






