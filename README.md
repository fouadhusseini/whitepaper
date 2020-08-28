# Open Insurance
The Open Insurance Initiative (OPIN) whitepaper. </br>
https://openinsurance.io
</br>
</br>
<p>This paper takes a high-level overview of the fundamental elements involved in incumbent insurers providing open access to their APIs allowing their customers to freely share with third parties their insurance policy information and much of the data collected on them by their insurers.
OPIN stands for Open Insurance and is a global initiative that sets out to promote deep integration with InsurTech  businesses and other third party service providers. It empowers the customer, heightens competition and most importantly aims to propel the insurance incumbents on a path that fosters better experimentation, accelerates implementation of leading edge technologies and hastens adoption of customer focused disruptive ideas. 
The recommendations herein are business-line agnostic, therefore the paper encompasses all lines of business, life and non-life, though the focus is entirely on the individual customer. All technologies and frameworks mentioned serve as example approaches providing those engaged in developing the API standard with the flexibility to recommend versatile guidelines and specification.
OPIN will become a community led initiative that could potentially be the largest insurance API project of its kind to date.
The main purpose of the paper is to promote the concept of open APIs in insurance paving the path for future in depth studies. It is hoped that it serves as the catalyst for further research towards determining the necessary uniform interfaces, processes, implementation plans and time frames.
</p>
<p><strong>1. Introduction</strong>

The digital evolution of insurance has seen greater investments  into startups looking to develop applications that extend insurance offerings and allow deeper links with the customer. This evolution has equally presented opportunities to incumbent insurers through deploying larger research and development budgets or by direct investment in startups.
Enabling greater access for InsurTech startups and software developers targeting insurance related activities may accelerate adoption of technologies such as blockchain powered smart contracts, prediction markets, internet of things (IoT), chatbots and robo-advisors and a huge array of other technologies.
Application Programming Interfaces (APIs) make data and services accessible that is otherwise locked behind corporate firewalls, they enable faster and easier development of web and mobile products, and they will allow insurers and individual consumers do business in new ways .
Uber and Pokémon Go use the Google Maps API to display location maps and routes, we share articles and videos when clicking the icons of Facebook, Twitter and LinkedIn using their APIs, goods are purchased and paid for when we click the PayPal button using an API, we book flights and hotels using Booking.com which aggregates information from tens and hundreds of airlines and hotels using…. APIs. It is a seamless, frictionless and secure end-to-end pouring of information to smart phones and laptops that the normal end user isn’t aware of.
This concept of interoperability is a hidden part of our digital business interactions on which we base our purchasing decisions, interact with others and perform our jobs. A study of API integration trends published in 2018 estimates that over 60% of businesses find that API integration is critical to their business strategy .
Open API access could allow data sharing between different insurers, with InsurTech startups, banks, and other businesses (can be collectively referred to as third parties).
Data, is defined as any piece of information that is collected. In the modern world we leave digital traces of personal data in almost every online interaction. Data is gaining greater significance as it can be analyzed and its findings used in providing businesses with profitable insights.
Given that underwriting is chiefly based on the analysis of historical data for carrying out risk assessment of policyholders, insurance is well suited for big data analysis. 
Our insurance experience will increasingly leverage APIs. A 2015 report found 79 per cent of consumers worldwide will use a digital channel for insurance interactions over the next few years .
Insurance data relating to personal or commercial insurance policies is currently not easy to share. Individual consumers can’t use their insurer’s portal to download machine-readable policy data, consequently neither can they easily share that data with any third party service provider either. This situation appears to be very common around the world. 

This is an area that’s definitely going to change. Governments and regulators are looking closely at what and how financial data can benefit consumers and entrepreneurs to promote economic and social development. 
The European Union has taken pioneering steps towards opening up access to data in the banking sector, the Payment Services Directive (Directive 2007/64/EC) , was designed to regulate payment service providers aiming to increase competition and the participation of non-banks (known as the challenger banks). The directive was replaced with the revised Payment Services Directive (Directive EU 2015/2366) . PSD 2, adopted on 12 January 2016, effectively broke the banks monopoly on users’ data through the concept of open banking enabling the innovative use of online and mobile payments developed by the FinTech startups. PSD 2 came into effect on 13 January 2018.
The government of the United Kingdom , in response to the PSD directive committed to accelerating the building of an open banking standard by conceiving its own Open Banking initiative , to take a lead in the implementation of open banking and foster the rapid growth of UK FinTech businesses. The Open Banking  data sharing standard came into effect on 13 January 2018.
In 2013, the Monetary Authority of Singapore and the Association of Banks in Singapore jointly produced “Finance as a Service: API playbook”  a comprehensive guide in identifying and developing API infrastructures in banks. 
The Australian government’s Productivity Commission notably publishes on its website a letter  containing the views of Mr. Scott Wilson, ex CEO of the Australian online insurance, finance and utilities aggregator, iSelect.com.au, in which he focuses on giving individuals’ power in the data held on them and proposes that such data should be in machine-readable formats with mandated secure access for real time data transfer via APIs.
The Ontario Securities Commission (OSC) in Canada, published on 16 March 2017, a whitepaper titled “Insights from Canada’s First Regulatory Hackathon” . It specifically highlighted; “Data that can be openly accessed, used and shared securely can benefit consumers and regulators. Open data has the potential to simplify a client’s onboarding experience by making core information about the client available to various parties and eliminating duplicative forms and processes.” It also added, “Open data may also be helpful to regulators. Regulators could potentially access this data on a real-time basis, making verification procedures faster and easier and improving auditing and oversight capabilities.”

There are a handful of examples of data sharing projects relating to insurance companies. One such example dates back to 2011 when four major US health insurers agreed to share their claims data with academic researchers at The Health Care Cost Institute. Aetna, Humana, Kaiser Permanente and the United Health Group allowed at least twice a year updates of data. The claims data, did not include identifying information about patients, the treating doctors or the care providers .
Another example is ACORD (The Association for Cooperative Operations Research and Development). Founded in 1970, it is a not-for-profit organization setting global standards’ for the insurance industry. Its standardized forms and certificates are used by almost 90% of property and casualty insurance carriers in the US. The forms and certificates cover some commercial lines such as; ACORD XML for Property and Casualty Insurance (request and response messages for personal lines, commercial lines, specialty lines, surety, claims, and accounting transactions.), ACORD XML for Life Insurance (XML specification based on the ACORD Life Data Model) and ACORD XML for Reinsurance and Large commercial insurance (request and response messages for personal lines, commercial lines, specialty lines, surety, claims, and accounting transactions). The forms are accessed through web browsers and mobile apps allowing insurers and insurance agents to share data electronically. However, it draws criticism   in that ACORD data standards are not actually standards but that they are merely suggestions, there are issues in that the quality of data downloaded varies greatly depending on the insurer.

















<strong>2. The potential benefits and opportunities resulting from enabling real time access to customers data</strong>

We will now examine key areas which highlight the tremendous potential of encouraging technology led innovators. 

2.1 Acceleration of growth in the InsurTech sector
The graph below illustrates that the number of InsurTech funding rounds saw consistent growth year over year. Specifically, the CAGR in funding rounds from 2012 to 2017 is 26%. In addition, the number of funding rounds in 2017 was 108% of that in 2016 .

 

2.1.1 Thriving scene of InsurTech incubators and innovation labs
Incubators are designed to identify innovative and disruptive startups that can swiftly address big opportunities with new ideas and solutions. Startups may be able to collaborate with established multinational insurers. Typically incubators provide mentorship, training, cheap and flexible office space, sponsorship from technology related companies and business support.
Some insurance incubators are stand-alone startup factories and others are investment arms of multi-national insurers.
Notable examples are, Silicon Valley Insurance Accelerator (SVIA), Swiss Re InsurTech Accelerator, W1 Forward InsurTech Accelerator, AIA Accelerator, DMZ InsurTech Accelerator, Global Insurance Accelerator and Lab of Forward Thinking by Manulife (LOFT). 

2.1.2 Investment in startups
Venture investing is at the heart of startup innovation. Now more than ever, well established insurers and reinsurers are taking this route to try and generate innovation for their businesses.
In 2013, Allianz X  was setup to invest in digital growth companies related to insurance. Likewise, AXA, launched a €200 million fund in 2015 to act as “an accelerating force for start-up companies” .
Munich Re is investing in InsurTech startups through its subsidiary Digital Partners  as it develops a new range of insurance products and alternative channels to sell insurance to consumers and small businesses.
These companies typically use small teams focused on identifying promising startups and understanding their business models. Some look to build strategic partnerships rather than to act purely as a venture capital provider but some are willing to do both at the same time. 
Accenture’s ‘The Rise of InsurTech’ report revealed that 44 percent of insurers across the world intend to pursue digital initiatives with startups from the insurance industry over the next two years. But more interestingly, 31 percent plan to work with startups from outside that industry .

2.2 Increased competition and pace of innovation 
Increased startup activities and consequently increased funding can benefit greatly from shared insurance data allowing startups and developers quicker access to data and freer space to choose partners and probably operate more independently.
Lower barriers to entry are also achievable through wider access to substantial data that would otherwise require many years to accumulate or be too expensive to acquire for a startup.
Not being fully open in the deployment of APIs would certainly constrain competition, especially in the consumer and SME segments.  Allowing for implementation of data sharing and open APIs will mean the creation of new competitive business channels, innovative new products, growth in customer base and enhanced customer experience.
Easier access for customers with the capacity to securely share and integrate their data with competitors that might have keener price points and more innovative or user-friendly functionality will be a welcome prospect. 
Insurers willing to adopt fresh solutions allowing quicker decisions will gain a definite advantage. It will incentivize incumbent insurers to develop and match innovative features offered by their competitors.

2.3 Extend services and partnerships to products beyond traditional players

It is very likely that with shared data and open APIs the playing field will become significantly larger allowing for financial as well as nonfinancial participants to participate in directly marketing an array of insurance products. 
These participants would find it very attractive to use open digital channels to derive commercial benefits out of their customers or members. Banks, building societies, mortgage companies, telecom operators , universities, trade associations, clubs, car dealerships and such like would be expected to take advantage of these opportunities allowing for increased revenues.

2.4 Insurers unlocking additional value out of sharing their data 
Data management now has strategic importance and is elevated onto the agenda of business leaders. While insurers use data as part and parcel of their business, it isn’t typically mined to extract customer insights. Third parties can extend an insurer’s reach to new customers and create additional values .
There is no reason why insurers couldn’t build any of the third-party services offered by the InsurTech startups. Encouraging third party integration and becoming a platform is potentially a strategy to mitigate the threat of being slowly eradicated by nimbler insurers. 
If anything, the fast moving InsurTech evolution forces incumbent insurers to adapt faster to capture emerging opportunities, tap into new revenue opportunities and provide improved customer experience.
Additionally, APIs can allow insurers to distribute data throughout their organizations as well as with third parties.
A heightened sense of adaption could potentially drive insurers towards monetizing proprietary data generating new revenue streams by processing their data into usable packages and insights for third parties. Traditionally insurers have lacked the interest to translate their data into a revenue source. Data monetization could be worth an estimated USD6-8 billion of annual profits for the insurance industry . The estimate doesn’t take into account open data but regardless, this report estimates that sizable revenue could still be generated out of monetizing proprietary data.

2.5. Smarter and more welcoming regulatory approach
While governments are usually keen to encourage more competition, the reality is that the cost and burden of regulatory compliance affects all participants but smaller players and new entrants are usually the hardest hit. Regulators need to become progressive, setup innovation friendly regulatory environments and be alert to new business models that require a degree of flexibility in regulatory approach.
An adjustment in the regulators approach to digital evolution, and a shift in the way in which the regulators engage with the industry and third-party service providers will deliver greater confidence to investors in general and startups in particular. A more engaged, consultative and focused methods of regulation will provide stable ground for the financial services to perform better and for competition to flourish.
This may amount to a cultural shift for some regulators and it should not go unnoticed that regulators setting growth and innovation as part of their objectives will help their national economies gain global competitive edge by attracting investors and InsurTech startups to their markets. Notable examples of such initiatives can be seen in Singapore  and Dubai  through FinTech hubs and large investment funds ready to vet and back promising businesses. 
Regulators opting to enforce the OPIN initiative will further focus this cultural shift and enable accelerated adoption of new technologies by insurers.

2.6 Better customer experience
Mobile applications, IoT (Internet of Things), machine learning and blockchain technologies are moving fast and so are the users. Cross industry technologies could allow insurers and users to stay in synch through allowing automated data access promoting easier, faster and more satisfying user journey.
Digital creativity will mean potentially cheaper insurance products, lower commission rates, more personalized, intuitive, convenient and flexible processes. PWC reported  that only 14 percent of consumers were very satisfied with communications with insurers and 44 percent of consumers indicated that they had not had any interaction with their insurers in the prior 18 months.
Customers can expect to see a major shift towards online and mobile channels, a richer, more holistic understanding of their needs, away from traditional channels, such as contact centers, one to one meetings with agents and paper forms.

2.7 Greater transparency with lower barriers to entry
Innovators struggle to get hold of the data and information they need , likewise customers do not feel empowered to access and use their own data.
New entrants to the insurance market will be able access a wealth of historic data on policy performance that they would’ve had to build from scratch. This provides each player in the market with equal opportunities to price risk more accurately and making better underwriting decisions.
Customers becoming better informed, means insurers will be forced to explain how they have come up with a particular premium, made certain risk assessments and loading criteria, rather than hiding behind mysterious formulas.



 
<strong>3. Standards and approaches powering API implementation</strong>

An API (Application Programming Interface) is a set of requirements that govern how one application can communicate and interact with another automatically.
APIs can be divided into two main uses: 
I.	Open (external/public) APIs 
Open APIs are an interface that has been designed to be easily accessible by the wider users of the web and the developers. These external APIs have to be on public facing portals and are usually designed as per the needs of the external partners and third-party developers. Fine grain security access based on partner usage models and subscription plans require API keys and security tokens to access the APIs. All functionality should be discoverable, allowing “client applications”  to fully utilize it.	
II.	Private (internal) APIs
Allows in-house software developers within the company (or contractors) to have access to parts of an organization’s backend data and application functionality to develop new internal systems or Apps. These applications may be circulated publicly but the API interface itself is unavailable to anyone not working directly for the API publisher.

A well-designed web API strategy should aim to support :
•	Platform independence
Any web or mobile client should be able to call and interact with the API, regardless of how the API is implemented internally. The essence of the strategy is to adopt widely used standards and protocols of data format and exchange.

•	Unhindered API evolution 
APIs can flexibly evolve and add functionality independently from client applications. As the API evolves, existing client applications are unaffected and can continue to function without modification. 

3.1	The building blocks of connectivity 
The paper will now describe existing data access technologies and current best practices in implementing an open (external) API approach.



3.1.1 API Architecture
The RESTful API architecture
Representational State Transfer (REST)  refers to a group of software architecture design constraints that bring about efficient, reliable, and scalable distributed systems. A system is called RESTful when it adheres to those constraints .
RESTful principles have gained wide adoption, the key principles being separating the API into pragmatic resources where these can be manipulated using HTTP requests. 
The main features of RESTful  application are:
•	State and functionality are divided into distributed resources. 
•	Every resource is uniquely addressable using a uniform and minimal set of commands (typically using HTTP commands of GET, POST, PUT, or DELETE). 
•	The protocol is client/server stateless, layered, and supports caching. 

3.1.2 Data Formats
JSON and XML data formats
JavaScript Object Notation (JSON) is an open standard format that is used to transmit data objects in the form of attribute and value pairs for further processing. JSON is commonly used for asynchronous communication between browsers and servers, the kind of communication performed by RESTful APIs and is favored over XML because it's cleaner and easier to work with.
XML (Extensible Markup Language) is also an open format that can be read by many applications providing a software and hardware independent way of storing, transporting and sharing data.
JSON has become a popular alternative to XML due to its terseness, quicker to read and write, uses arrays and can be parsed faster, qualities that are winning developers over. It’s just a data format with no frills added.

3.1.3	Security and access control
The broad goals of security and access control measures are as follows:
•	Securely encrypt data being exchanged
•	Guarantee the identity of one or both parties
•	Prevent data tampering
•	Prevent replay attacks 
A range of standards are detailed below to give a general overview.
3.1.3.1 OAuth 2 authentication standard
An open protocol to allow secure authorization in a simple and standard method from web, mobile and desktop applications  enabling third-party applications to obtain limited access to a web service. 
OAuth 2 provides various "grant types" for serving different use cases. These are defined as “Authorization Code” for Apps, “Password” for logging-in with a username and password, and “Client credentials” for application access.
The standard focuses on client developer simplicity while providing specific authorization flows for web applications, desktop applications, mobile phones, and living room devices .
This means that end users get access to their data while protecting their account credentials. For browser or mobile Apps, this is usually accomplished by displaying an interface provided by the App to the user.

3.1.3.2 Transport Layer Security (TLS) encryption of data standard
This is a basic level of security which rides on the Transmission Control Protocol (TCP) and HTTPS. All RESTful APIs by default are created to use this as an encryption mechanism. TLS and its predecessor, Secure Sockets Layer (SSL), both of which are frequently referred to as 'SSL', are cryptographic protocols designed to provide communications security over a computer network .

3.1.3.3 Online Payment standards - PCI DSS
This item may not be directly relevant to API architecture, however given the importance of securing credit cardholder information and payments handled through Apps and websites in the purchase or renewal of insurance policies, it is important that conformity with international security standards relating to online hosting are implemented.
The Payment Card Industry Data Security Standard (PCI DSS)  is a proprietary information security standard for organizations that handle most branded credit cards from the major card schemes including Visa, MasterCard, American Express, Discover, and JCB. 

3.1.3.4 Two Factor Authentication (2FA)
This is an additional layer of security requiring a second piece of information other than the password. With the use of 2FA, websites and Apps can be doubly confident of the user’s identity and allow access to their account.
Most common types include SMS text messages while the most popular are called software tokens employing 2FA Apps  that provide time based one-time passwords.
3.1.3.5 OpenID Connect
OpenID Connect is a simple identity layer on top of the OAuth 2.0 protocol. It allows clients to verify the identity of the end-user based on the authentication performed by an authorization server, as well as to obtain basic profile information about the end-user in an interoperable and REST-like manner  . 
This authentication process defines specific fields for including profile information like address, phone number, email and other fields using, for example, a Google, Twitter or Facebook profile.
OAuth 2.0 is the substrate for OpenID Connect, and as such, utilizes HTTPS (specifically TLS/SSL) infrastructure for data security . 

3.1.3.6 JSON Web Tokens (JWT)
JWT is an open standard that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed. JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA .

3.2	Emerging technologies and API styles to consider 
To conclude the roundup of recommended technologies it’s important to also list various emerging technologies, protocols and frameworks currently gaining greater adoption, in pursuit of an ever more advanced edge in executing this initiative.

3.2.1	Blockchain protocols 
Blockchain protocols  have special characteristics that insurers can employ and as the B3i initiative  recently demonstrated, blockchain can produce 30% gain in productivity.Smart contracts can store, verify and execute the terms of an insurance policy. They would contain a set of rules where one rule triggers subsequent actions until the contract is completed. These rules are stored in the blockchain and all related rules and actions would get reflected in the ledger. For both insurers and customers, smart contracts offer the convenience of letting transactions be done between them directly, disintermediating the customer relationship.
While smart contracts (taking the Ethereum blockchain as an example) cannot access and fetch data from the internet, (e.g. retrieving weather-related information for a crop insurance policy), APIs could be configured to be smart contract enabled to use services provided by the likes of Oraclize and iExec, providing a reliable connection between web APIs and decentralized Apps Dapps). Blockchain is obviously not an API technology but is mentioned here due to the increasing need to have API’s configured and architected in blockchain/smart contract friendly setup. 
3.2.2	ODATA
Originally developed by Microsoft in 2007, the Open Data Protocol (OData) provides a uniform way to query and manipulate data sets through CRUD operations (create, read, update, and delete) . OData is well established among companies such as Microsoft, SAP, IBM and Salesforce. It allows the creation and consumption of queryable and interoperable RESTful APIs in a simple and standard way and is quickly gaining ground for its open source approach, as well as its exceptional scalability.

3.2.3	GraphQL 
Developed at Facebook in 2012, GraphQL  is a data query language deployed at companies such as Facebook, Shopify and Intuit. It provides a complete and understandable description of the data in an API, gives clients the power to ask for exactly what they need, makes it easier to evolve APIs over time and enables powerful developer tools.
As an API technology, GraphQL is finding its place in the broader API market landscape and has potential to strengthen adoption by leveraging two other API sectors: Serverless  and the Internet of Things (IoT).

3.2.4	JSON API
JSON API  is touted as the simple alternative to GraphQL and REST. “By following shared conventions, you can increase productivity, take advantage of generalized tooling, and focus on your application. Clients built around JSON API are able to take advantage of its features around efficiently caching responses, sometimes eliminating network requests entirely” as their official website explains.
A focal goal of the specification is to optimize HTTP requests, both in terms of the number of requests and the size of data packages exchanged between application clients and servers.

3.2.5	Hydra API
Hydra  is one of latest projects on the API scene perhaps unknown to great many developers but appears to be promising. 
Hydra is a set of technologies that allow the design of APIs in a way that enables smarter clients. The foundation is laid by the Hydra Core Vocabulary which defines a number of fundamental concepts, such as hypermedia controls and collections, which allow machines to understand how to interact with an API. Since all information about the API is available in a machine-readable form, completely generic clients become possible. The Core Vocabulary is complemented by Linked Data Fragments, a set of specifications that enable advanced yet efficient client-side querying of Web APIs. 

3.2.6	OpenAPI Initiative
The OpenAPI Specification is a community-driven open specification within the OpenAPI Initiative, a Linux Foundation Collaborative Project .
At the heart of the API description format is the Swagger specification, which was donated by SmartBear software as the basis for the open specification. It’s an open description format for API services that is vendor neutral, portable and open.
The specification, has picked up tremendous traction in API development, and is seeing adoption by thousands of API developers and consumers.

 
<strong>4. Shared data: Access and usage</strong>
 
Different regions of the world have different standards and inclinations towards sharing of data, for instance, in the Middle East, compiling insurance statistics from published research is very difficult and, in some cases virtually impossible, publicly available data is almost non-existent. 
There are however instances where insurers have willingly and voluntarily published data. Zurich International Life , claims that it is “the only life insurer in the Middle East to publish yearly claims statistics”. 
This is a case where an insurer sees strategic advantage in promoting its transparency through its willingness to share its data, for free, with its customers and competitors.

4.1 Data literacy and the public’s perception of shared data 
Sharing of private data is a new concept in insurance. Although minimal public research or surveys related to sharing of insurance data were available for use by this paper, there are however, few that studied the open banking projects in the EU and the UK. These studies can be relied upon to gain a generalized view of the public’s perception of making available private data and its use.
Research from Accenture conducted in the UK in 2017 , finds that, “69 percent of consumers would not share their bank account information with third-party service providers. In fact, more than half (53 percent) of consumers said they will never change their existing banking habits and adopt open banking”.
Experian  commissioned research to understand the UK consumers attitude to data sharing. What it learned was that there is an issue explaining and understanding the ‘value exchange’. Consumers will share data if what they get back is sufficiently valuable to them in return. Less than half (41%) will consent to their data being shared, but they are not enthusiastic about it. They simply see the exchange of information for products and services as an inevitable trade-off. 
A more revealing study published by Ipsos MORI  puts into perspective the views of consumers across the globe. The following table highlights one of the key issues. 





Would you be happy to share your personal financial data with third parties to use their services?
Banking markets	Yeses in percentage of total
Developed markets
France	9
Canada	10
Japan	11
UK	13
Switzerland	15
Poland	16
Norway	17
USA	19
Developing markets
UAE	35
Saudi Arabia	42
S. Korea	47
China	60
Source: Adapted from Ipsos MORI, Open Banking Global Study.
These figures suggest that consumers in developed economies will have to be persuaded to change their attitudes and behaviors. This should lead to deeper probe of the issues making people unhappy about sharing their data.
Personalization of insurance means new and additional sources of information (much of it may be through social media, activity, location tracking etc.) are used to reveal information about behaviors and lifestyles providing for better assessment of risks but this could of course raise additional privacy concerns.
Third party service providers must engage with and convince customers of the relevance and practicality of their innovative new services, communicating clearly with them to demonstrate the potential monetary and non-monetary benefits of giving consent to sharing their data, whether to receive meaningful discounts, gain better coverage or receive elevated levels of service and convenience. 
Customers’ trust can be reinforced by dispelling their fears of data hacks, internet fraud, cyber-attacks and viruses by reinforcing the notions of secure data management.
 
4.2 Insurers opening up to data sharing
The importance of regulation can’t be understated, in particular, regulatory policies concerning access to and use of personal data. In a digital society, these policies have to strike a difficult balance between ensuring privacy and promoting competition and innovation in the context of permissioned data access and APIs. This paper, of course, advocates smarter regulation (please refer to Section 2.5), noting that important tradeoffs may have to be made. 
To clarify further the concept of what personal data could comprise (in the context of insurance services), a classification of the main types of data is needed:
1-	Financial data collected by business and government
a. Data collected and held by insurers and intermediaries in the course of their business. 
The data relates to insurance policies, retirement planning, personal wealth, schooling plans etc.
This information is considered private and confidential, subject to data privacy laws and can’t be shared without the specific consent of the customer.

b. Data held by government agencies and institutions on individuals
The data relates to insurance, taxation, medical records, criminal records, credit rating etc. 
It is important to take note of various Open Government/Data projects in countries such as Canada, Australia, USA and the UK. This open type of data is anonymized and aggregated before being shared or released.

c. Data held by banks and other financial institutions 
The data mainly relates to current and deposit accounts, loans, mortgages, investments and insurance.
This information is considered private and confidential, subject to data privacy laws and can’t be shared without customer consent.

2-	Personal and lifestyle related data available on social media channels 
Personal data shared by individuals through the social media channels (LinkedIn, Facebook, Instagram etc.). The data relates to friends and family, education, religion, career, personal interests etc.
This information is considered private and confidential and can’t be shared without the consent of the customer.
 
It is now widely acknowledged that businesses take advantage of a varied scope of data sources to enrich the knowledge they hold on their existing or prospective customers. This data can be intra-industry as well as inter-industry. Insurers can potentially combine their data with that from health providers or banks to gain deeper insight on individual customers.
Putting consumers in control of their data means they choose what to share, with whom, and when. Third parties gain access to that data when the consumer grants it to them and once the data has been used for its intended purpose, the consumer can subsequently revoke that access.
In the context of the proposed open insurance initiative, insurers will make available to third parties the data they hold on their customers through public APIs satisfying the following aspects:
1-	Access and revocation of access to data is controlled by the Insured
2-	Insurers provide access to everyone, for example, competitors and InsurTech startups, through secure and open APIs
3-	Private data is made available free of charge when customer gives permission to do so
4-	Data is presented in a machine-readable format according to a specific industry standard and format 
5-	The customer (the Insured) has the ability to grant access to unlimited number of third party service providers
Elements to consider, third parties initiating access to insurers API:
1-	A third party must receive explicit consent from the customer to access their insurance data. 
2-	Apps and websites must make clear the reasons necessitating access to this data
3-	Data received is kept safe and secure and not shared with or sold to other parties 
4-	An authorized third party must handle the data in compliance with prevailing data privacy rules and regulations (jurisdiction specific)
5-	App or the website must inform the customer that their login credentials will not be shared or saved by the 
6-	Customers are solely responsible for the validity and efficacy of the services that a third party provides when connecting to their Apps or websites
7-	The customer is able at the press of a button to permanently remove all of his data from a third party App if he wishes to do so

Elements to consider, insurers providing permissioned access to data:
1-	Insurers must provide customers with login credentials to a web dashboard enabling access to an insurance portal.
The portal includes a functionality to allow the customer to view all the Apps and websites accessing their data. The customer can at any time directly revoke access previously granted to a third party.
2-	Insurers will provide automated and unhindered access to a sandbox environment. Pre-verification of the third party will not be required before gaining access to the sandbox.
This paper recommends applying a process of checks and a unified set of verifiable requirements for third parties to meet before accessing production API environments. (Refer to section 4.4).
3-	Third parties will have, read as well as write access to the customer’s data. 
Read access to data is allowing third parties to view customer’s insurance information, while write access is allowing third parties to issue, cancel and amend policies and their coverage.
4-	Data flows must occur in a secure and safe manner
5-	Only the data types authorized by the user is shared with third parties

4.3 Data privacy
Different data warrant different levels of privacy, and informed customer consent implies an understanding of the implications of sharing data when approving third party Apps. For instance, medical and life insurance data may carry more privacy weight than data related for instance to motor or home and contents insurance.

GDPR
The new General Data Protection Regulation (GDPR)  rules came into effect on 25 May 2018 and attracted a lot of attention across the world. As mentioned earlier, it would be futile to discuss different national data privacy regulations and acts, however, for the purpose of clarifying what GDPR has introduced, a brief introduction would be in order to inform the reader of its most important elements.
GDPR basically requires that unambiguous consent must be given by the user through a statement or a clear affirmative action, subject to the data being collected for specified, explicit and legitimate purposes. This regulation is mandatory for all organizations operating across the EU and processing personal data of EU citizens.
It ultimately requires compliance with more stringent data protection than ever and updates of systems. Citizens will be able to demand detailed information on the source of the data held on them, the categories of data held, the purpose of data processing, the retention duration and the different parties that received it. In essence giving EU citizens control over their personal data.

The OPIN initiative encourages the alignment of the interests of the insurance industry with that of the consumers to enable the free flow of data necessary for allowing InsurTech startups and other third parties the capacity to partake in a wider competitive landscape. 
It’s important to highlight the main aspects of reinforcing data privacy:
1-	Any processes or transactions must be authorized using strong authentication and security protocols 
2-	Apps developed by third party service providers must be listed in a central Apps store if service is to go live and into production 
3-	The customer has to give explicit permission for his data to be accessed
4-	Insurers must create confidence. They must educate their customers about Open Insurance, assure them of their secure systems environment and guarantee accountability and customer protection against mal-use of their data.
5-	Adopt a system of penalties to dis-incentivize mal-use of data by third parties

Third party service developers, have a job to do too, in promoting the aims and key benefits of shared access to data. The most difficult issue here is educating end users on data permission and privacy. 
This paper can only take an overview of the main aspects of executing an open insurance initiative and is intentionally not specific to a particular market or country therefore fine-tuned data privacy solutions will have to be proposed at national levels.
Participants and stakeholders in each market must therefore prepare a detailed study of such requirements to ensure full compliance. Such a study should support the adoption of this proposal while maintaining high levels of customer protection and privacy. 

4.4 The verification of third parties to access open APIs: The Apps Store
As has been explained above, access by third parties to insurer’s APIs should go through a process of checks and approvals.
It is recommended that an online App submission service is setup and forms part of a central OPIN initiative setup (refer to section 7.1) that is tasked to test and approve the Apps to ensure that they include no malwares or functions that could in any way affect insurers systems or customers devices. This service would centralize all App reviews, approvals and listing in the Apps store. 
The central verification service will allow all App developers to go through the review process only once, reducing costs and administrative burden on insurers as well as third parties.
The review and approval service would minimally test for two things:
1-	Code is safe for customers and insurers in that it does not introduce malwares or extract personal data other than what has been advertised by the App developer or agreed to by the customer.
2-	Testing the App’s authenticity in that it provides the service that it describes to be offering.
All Apps must be tested and reviewed prior to the release of new versions to maintain safe status and listing.

4.5 Scope of data
This section outlines the two types of data that insurers should be able to provide to third parties.
4.5.1	Data specific to the Insured (Insurance policy data)
Data relating to insurance policies in force and that relating to prior years (of up to 5 years). 
It’s important to give an example of the types of data that are recommended to be treated as the minimum required, the below product examples should clarify.
Private Comprehensive Motor insurance policy:
•	KYC information
•	Policy coverage, sum insured, deductibles, policy duration and beneficiaries.
•	Type, make, model, age and specification of vehicle insured 
•	Premium rate or total premium charged
•	Brokerage or commission payments
•	Policy fees, taxes and other charges
•	Claims history. An itemized listing of claims paid and outstanding including cause of loss, net settlement amounts and recoveries
•	Data collected from telematics devices 

Term Life insurance policy:
•	KYC information
•	Age, height and weight of the life insured
•	Policy benefits  
•	Premium rate or total annual premium charged
•	Policy fees, taxes and other charges
•	Brokerage or commission payments
•	Beneficiaries
•	Medical test records
•	Data collected from wearable devices

4.5.2 Information and data specific to insurers business 
The following are some examples of the minimum types of information that can be made available over open APIs.
•	Open Data (refer to Open Data description below)
•	Online signup links for obtaining login credentials to insurers portal
•	Information on products, offers, and services the insurer offers
•	Fund performance data (life insurers)
•	Links to customer service and complaints portal, help centers or chatbots
•	Lists of medical network providers and approved car workshops 
•	Insurer’s office locations, opening hours, financial results and news 

4.6 Open Data (anonymized and aggregated data)
Open Data refers to data that is non-personal (data that had undergone anonymization and aggregation), to the extent that it does not contain information about specific individuals. It is free and open for anyone to import, download and use, due to the valuable role it plays in research, in shaping public policy and helping business to identify new opportunities. 
The Open Data Handbook , uses the following concise definition “Open data is data that can be freely used, re-used and redistributed by anyone - subject only, at most, to the requirement to attribute and share alike.
The main pillar of Open Data is interoperability, which allows diverse organizations and systems to easily combine different datasets together to gain enhanced insights. In the context of insurance, such insights could lead us to:
•	produce personalized products that closely match customers’ lifestyle and preferences
•	better customer segmentation
•	enhanced underwriting leading to better pricing of insurance products 
•	better fraud detection and smoother claims handling 
These serve as basic examples of the potential benefits achievable through sharing of Open Data. The real benefits are achievable through mash-ups of insurance data with banking data, open government data and other datasets.
Common interoperability standards and data sharing architectures in real-time analytics are necessary to deliver the hoped-for solutions promising to transform the insurance industry. 



Types of data to treat as insurance Open Data
The following are basic examples subject to wider insurance sector consultation to propose a dataset and the format for what will be treated as real-time Open Data generated by insurers:
•	Statistics on customer complaints
•	Causes of vehicle accidents
•	Insurance fraud 
•	Statistics on homeowners and renters insurance losses
•	Statistics on natural and man-made disasters
•	Personal financial planning data
•	Data on the performance of health providers

4.6.1 Real-time access to Open Data
Several studies have found that real-time Open Data and insights can provide a tremendous level of transparency and accessibility improving decision making .
The insurance sector will be able to receive up to date insights, and the benefits will extend to InsurTech firms and other third parties providing them a level playing field and a wider perspective.
The OPIN initiative advocates the development of data formats to accommodate real-time provisioning of Open Data over open APIs.
The OPIN website could act as a platform to harvest and catalogue real-time insurance Open Data (refer to section 7.1), cataloguing this data on regional basis and per line of business basis, facilitating global research and unearthing significant commercial opportunities.

4.6.2 Privacy concerns regarding Open Data
Developing an open insurance initiative requires a balanced agenda that protects personal identity, restricts exploitation by business and communicates a clear message of trust and privacy to consumers. 
Privacy of individuals can be affected where identity can be inferred from data. This may be the case when microdata is also released. Microdata  is defined as data released in its most granular and unaggregated form. 
Most laws, regulations, and internationally recognized guidelines provide frameworks for privacy and data protection but most were not created with open data in mind. Moreover, finer granularity and the inclusion of microdata could cause a lot of concern in that this data, could through various techniques, de-anonymize its owners revealing what could be highly sensitive personal information.
It is probably more pragmatic for the purpose of the Open Insurance Initiative to only support the release of fully anonymized and aggregated data leaving out microdata types that could introduce a lot of complexity and concerns.	
 
<strong>5. Concerns potentially obstructing the adoption of the OPIN initiative</strong> 

A number of core challenges affecting the implementation of the Open Insurance Initiative are explored.

5.1	Concerns over the shortcomings of legacy IT systems
Most insurance companies are dependent in large part on legacy  IT systems. There may be many cases where core systems are an amalgamation of different systems built on different technologies at different eras, coded to run independently, but were later hinged together as business demands changed or when new web services were introduced.
Some insurers could raise objection to this initiative referring to some of the difficulties that could arise in implementing open API access on top of legacy systems.
Fortunately, microservices  represent one of the most promising avenues towards executing an API strategy, allowing for monolithic  services to be broken down into smaller and reusable service components. Companies that employ this approach will realize greater project delivery speed and security. The use of microservices is a fundamental enabler to the implementation of open APIs. 

5.2	Security concerns 
There are inherent risks to be recognized from an open API standard. APIs represent a growing security risk in the way they expose access points for hackers to try to access an insurer’s sensitive data. According to a 2018 poll by Imperva , of 250 IT professionals polled, 40% of organizations consider bots and DDoS as top security threats followed by authentication enforcement at 25%.
Customers will be communicating with many more instances than just their insurer, multiplying the exposure surface for hackers. According to a Verizon 2016 Data Breach Investigation report, approximately 40% of all data breaches occur via web applications.
The insurers should assume as much of the security responsibility as possible. A variety of standards for the security of data and securing access to APIs are discussed in section 3.1.3. There are additional security features that can be employed such as enforcing a system wide quota so that the backend cannot be overloaded (i.e. throttling), implement password strength requirements, concurrent connection limitations and session length and requiring periodic re-authentication and authorization for continued use.
Additionally, ‘white hat hacker’ services can be used. These hacker services are often hired by companies to probe security and identify exploits for patching up vulnerabilities.
Individual customers must also have an awareness of their rights and responsibilities when sharing their data. They must be informed on what consent means in connected insurance.

5.3 Lack of strategic foresight in adopting open APIs 
In absence of governmental or regulatory vision leading to the adoption and enforcement of insurance open initiatives, the onus will fall squarely on innovators among the incumbents to voluntarily and collectively pursue disruptive business models. Insurers traditionally haven’t been very good at demonstrating innovation in technology, products, channels, or services and enjoyed being protected by high regulatory barriers to entry. 
While most insurers see economic value in private APIs, open APIs remained a special case. The deterrent often is the management buy in of the concept. There is natural tendency in the financial services to being apprehensive and tentative at first of innovative solutions until early adopters take the lead and these innovations become reality.
Assuming that markets lack the incentives to embark on this transformative journey, or assuming that the obstacles are far too unsurmountable, or incumbents resist and obstruct the initiative, what would come of this initiative?
The paper takes an optimistic view, nonetheless there’s a possibility of failure. If lessons have been learnt from other industries, we know that innovation waits for no one, entrepreneurs with fabulous new ideas and tech stalwarts such as Apple, Google and Amazon  are working towards changing the industry in a massive way. 
If this initiative fails to become widely adopted by the insurance industry, it could serve as a guide to other industries that may find opportunities in collaborative initiatives aiming to put the customer experience at the forefront of their strategy.


 
<strong>6. What technologies will startups be able to power with the data?</strong> 
 
By adopting open APIs, insurers can more readily experiment, collaborate and leverage innovative solutions and business models that InsurTechs’ have or are developing. 
There is obviously a lot that goes beyond the perfunctory aggregators and price comparison sites to a world of startups perfecting data analytics, machine learning, visual recognition and natural language processing. 
Symbiotic relationships can be leveraged in both directions, InsurTech firms channeling customers to insurers and vice versa where insurers provide customers to InsurTech firms that are able to provide complimentary services.

6.1 What will this connectivity to API endpoints and access to data introduce?
Presented here are example technologies benefiting from open APIs. 

6.1.1 Virtual Reality (VR) and Augmented Reality (AR)
VR is about immersion, users don headsets equipped with applications that replace the real world with a virtual environment. AR leverages software on smartphones or heads-up displays, such as smart glasses, to overlay digital information, including images and text, atop physical objects in the real world.
Developers are experimenting with virtual technologies for use by loss assessors and claims staff by creating virtual mock-ups of damaged cars and homes for training purposes.
Others are creating virtual reality games designed to walk the customer through the completion of health screenings (e.g. measure heartbeat and pulse) towards insurance proposal completion or receiving relevant health information.
Life insurance expert avatars can interact with customers wearing VR headsets in a 3D-simulated environment and respond to questions and policy servicing requirements.

6.1.2 Blockchain platforms
A blockchain is a distributed register to store static records and dynamic transaction data without central control using consensus-based models to check the validity of transactions. Most essential properties are those of transparency and privacy making information sharing secure and seamless.
Automation through smart contracts  is currently a hot topic (e.g. the Ethereum  blockchain). The code of a smart contract can establish rules and consequences that can be automatically executed reducing the cost of payment processing, risk assessment, underwriting and claim processing.
KYC profile verification can be securely implemented through blockchain. A customer can forward the verified identity data to different companies for different smart contracts using one App, avoiding the need to repeat the same identification and verification process.
IoT devices fitted in cars, homes and factories can communicate with insurance smart contracts, enabling automatic detection of damage and triggering repair processes, as well as claim payments.
Distributed ledgers can track valuable items by validating ownership, authenticity and origin of goods and documents.

6.1.3 Analytics and Big Data
“Big data refers to the massively increasing volume, velocity and granularity of data sets that are being accessed and linked. The ability to compile and analyze those very granular data sets is now transforming the way insurers see large pools of consumers and how they price risks.” 
Big data can be used by motor insurers in predictive modeling by cross-referencing user behavior and lifestyle habits data with external factors such as road conditions and types of neighborhood to assess whether the driver is likely to be involved in an accident, or have their car broken into or stolen.
Insurance companies can offer personalized products and lower premiums, contact the customer for special offers when they are likely to shift to a competitor or offer a family-product when a family is likely to have a child.
Software can apply data analytics to calculate litigation tendency scores to define which accidents and claims are more likely to result in a dispute or a legal case allowing insurers to assign those claims to more experienced adjusters helping conclude those claims more efficiently for lower sums and with less time.

6.1.4 Connected insurance, wearables and IoT
Wearables are basically sensory devices with access to networks designed to perform computing and information exchange functions. In the context of wearables, Capgemini’s  classification of sensory devices into wearables, nearables and hearables is apt. Such devices would include fitness bands, smart contact lenses, internal biomonitors and genetic mutation sensors.
Wearables could have a significant role to play in life insurance underwriting. A smart ear device could collect biometric and lifestyle data (e.g. heart rate, temperature, movement speed, and distance tracking) while simultaneously playing music to the wearer. Hearables could become the next wearables . The data collected will be of significant importance when integrated with underwriting, claims analysis and real time feedback on keeping track of health goals.
Health insurers are able to offer customers agreeing to the use of fitness tracking devices, premium reduction incentives for healthy activities and eating.
Data collected through these devices could also be used in court cases to support or deny claims by showing that injuries suffered by the insured person are not as serious as claimed and may even prove a fraud instance.
The term IoT  also includes sensors connecting physical properties to the internet such as vehicles, buildings and other items “embedded with electronics, software, sensors, actuators, and network connectivity that enable these objects to collect and exchange data.” 
Use cases of such devices would provide advanced level of information and rich insight to allow Usage-Based Insurance (UBI)  models and strategies.
A vehicle insurer, can track mileage and driving behaviors (e.g. driver keeps safe distance, parks slowly, and always comes to a complete stop without hard braking) using odometer readings and in-vehicle telecommunication devices that are usually self-installed into a special vehicle port or already integrated in original equipment installed by car manufacturer. The customer would be rewarded with a competitive policy and the insurer keeps a customer with a lower risk profile.

6.1.5 Machine learning and automation
Machine learning (ML) represents the leading edge of artificial intelligence (AI) and the term is used to describe the idea of teaching computers to learn in the same way humans do.  Since insurance is data heavy, it is perfectly poised to be significantly impacted by AI. 
Here are just a few ML concepts and algorithms to note:
-	Support Vector Machines (SVM) 
-	Conditional Random Fields (CRF)  
-	Neural Networks 
-	Bayesian Networks 
-	Genetic and Evolutionary Algorithms 
-	Decision Trees 
ML algorithms could be used to extract information in handwritten and typed forms and emails into a digital form with very high accuracy, enabling faster underwriting, offering new products, cross selling or even recommending switching to a better insurer. 
Machine learning software can detect complex claims from human interaction and data early in the lifecycle and highlight them for deeper investigation and action by humans if necessary. 
Chatbots  and AI assistants respond to customer inquiries and provide guidance on renewing their policies or solving their claims.
Automation is the key to success in machine learning. 

6.2 Use cases
The following are basic demonstrations of services that could be made available. The overarching emphasis of this initiative is the development of ever more sophisticated utilities providing the customer with transformative experience through cheaper and highly accessible products.

6.2.1 Life insurance
Providing open APIs could introduce a wide variety of third party service providers. They may include; other competing life insurers, P&C insurers, brokers, banks, credit unions, employers, lawyers, accountants and financial planning advisors.
API scenarios may include usage by banks and mobile telecom operators marketing term life insurance or endowment plans to their customers. Getting life insurance is often required by banks from clients seeking to obtain a mortgage.
The API will provide an interface for a Bancassurance operation to retrieve life insurance policy details from the customer’s insurer as well as data collected through wearable devices collected by that same insurer. The details will include accident and claims history, premiums paid, fees and charges borne by the customer.
APIs could be used by accountants or lawyers who may offer Keyman insurance for succession planning. 
Third party service providers will be able to integrate an insurer’s life product into a user interface displaying the different offerings available from a collection of insurers. They could for example perform portfolio analysis, provide advice on retirement planning, tax treatment of insurance proceeds and many other functionalities.

6.2.2 Motor comprehensive insurance
New opportunities are being explored through connected cars and other personal means of transportation. Embedded hardware, onboard software and mobile Apps offer a combination of personalized entertainment, communication, intelligent route planning, improved vehicle maintenance, operational efficiency and emergency assistance. 
Customers can capitalize on a variety of data from their connected cars to receive new benefits, have their risk assessed more accurately, and benefit from insurer tie-ins with other co-marketed services.
DApps powered by smart contracts could be developed to automate accident notification to insurers on behalf of the customer, robotic assessment of who is at fault, reporting fraud incidences and affect prompt settlement of claims.

6.3 Sample utilities and tools
We’ll now take a look at sample additional utilities that can be offered to customers as well as insurers through various digital means:
•	Appointment scheduling with nurse, doctor or sales agent
•	Alerts and notifications
•	Assistance and emergency services
•	Life event detection
•	Like-minded community detection
•	Influencer analysis
•	Hobbies and interests profiling
•	Gamification and incentives for customers 

The samples of use cases and utilities are only a demonstration of the possibilities and functionalities that can be provided but the most interesting tools and uses could still yet to be created. Killer insurance Apps could bring about meteoric growth in new and existing lines of business for the individual as well as the corporate customer. 

What follows next are graphical representations of the aforementioned use cases.

 

 








 
 
<strong>7. Recommended approach to implementing the OPIN initiative</strong>

This paper has set out the reasoning behind creating an open insurance standard as well as an overview of the key aspects of implementation.
Incumbents through sharing data will be prompted to develop better ways of engaging with customers, develop new commercial models and allow the economic and societal benefits of wider access to data to emerge.
The key requirements for an open API framework should take into consideration the following aspects:
1.	Design API standard that is simple and intuitive to maximize developer productivity and success. Leverage a body of best practices such as using concise versioning, rich API documentation and code samples.
2.	Avoid proprietary software, instead, use open source software, repositories and web standards. 
3.	Develop an industry standard with a minimum dataset which all insurers must offer via their APIs.
4.	Be guided through observing successes and failures of other open initiative.

7.1 The creation of the Open Insurance Institute
A central entity has to be setup to initiate, coordinate and lead the activities progressing the international adoption of OPIN by insurers. The institute will be a not-for-profit international standardization organization representing the open community of developers, insurers and users committed to enabling and promoting the open API initiative.
Insurers, InsurTech companies, regulators, actuaries and others interested in partaking should join the institute. A technical steering committee composed of a mix of talents will work towards directing the work for the recommended API specification.
The OPIN Institute will encourage the setup of working groups to orchestrate national level debate and agreement on datasets, Open Data and data privacy.
The Institute will: 
•	Propose and develop an API standard
•	Provide consultancy services and guidance to regulators and insurers on technology and security
•	Promote and coordinate cross industry cooperation
Other key tasks of the institute include:

Communication 
Communicate extensively with major players in the insurance industry, regulators, developers, and consumer protection groups. Engagement shall be through meetings, press releases, press interviews and social media to accelerate adoption of the initiative.
Knowhow and Education 
This will include discussion forums, documentation, samples of code and training aiding easy participation.

Central screening of Apps
A central screening framework is crucial to the implementation of the OPIN initiative requiring extensive consultation with the InsurTech community. The institute will handle screening and listing of all Apps in the Apps Store.

Website resources 
The OPIN website will be gradually developed to host a blog, FAQ section, API register and Apps store, guides and documentation. 
The OPIN website could additionally act as a platform for harvesting and cataloguing real-time insurance Open Data, on regional basis and per line of business basis.

7.2 Building a community of contributors 
The initiative by its nature is not aimed at a specific market and will rely on a international community of collaborators in kickstarting and progressing the initiative. Experts, developers, entrepreneurs, Fintech and InsurTech communities from all over the world are encouraged to participate and contribute to the OPIN initiative.

7.3	Working groups
It is recommended that working groups are setup at national level (for example OPIN Working Group in Canada, OPIN Working Group in USA, OPIN Working Group in UK etc.). These will be independent national groups of InsurTech experts, insurance practitioners, data privacy and intellectual property consultants, developers etc. The working groups will not be administered nor controlled by the Institute. Their key role will be to:
•	Coordinate local consensus on the scope of data and its privacy.
•	Engage, educate and coordinate national discussions 
•	Promote the proposed open API standard delivered by the OPIN Institute
•	Recommend national implementation plans and time frames

7.4	The OPIN API standard
The task of deciding on the specification of the open API standard would be the domain of the OPIN Institute through wide consultation under the direction of the technical steering committee of the Institute.
Such consultation would necessarily encompass insurers, developers, startups and experts in the preparation of API specifications to reach a vendor-neutral, portable and open specification.
The standard will be subject to a separate paper guided by the recommendations of Institute’s technical steering committee and the input from the working groups.

7.5	The approach incumbents need to take
The most important aspect of joining the API movement is for incumbent insurers to prepare their companies for public APIs starting with an appraisal of internal processes to prioritize their investments. 
Incumbents must become agile in building human talent and technical resources supporting API deployment, real-time data generation, simplified automated processes and transactions.
Organization and governance wise, it might be necessary to setup a core API team  championed by an executive steering committee allocating funding, resources and monitoring KPIs. The core team would be directed by an API product manager overseeing API developers and operations. Governance is an important subject, it should instill an emphasis on quick delivery (time to market) and address critical concerns early on be it technical, organizational or legal. A recent survey  has found that 38% of businesses indicated that the average number of days needed to build new API integrations is 30 days.
Insurers of different sizes and specialties must work toward achieving as big of a competitive advantage as economically possible by internally embarking on a review of the value chain enhancing aspects such as the system/s architecture, customizability and ease of product configuration, providing 360 degrees view of the customer, automated underwriting and claims process flows, systems availability, scalability and security.
Continuous evaluation and monitoring is part and parcel of achieving a high standard of connectivity ensuring that API consumers are happy with the service and not hampered with returned errors, down times and slow responses.  The core team should keep an eye on API usage including number of Apps driving usage, usage patterns and volumes and types of data requested.

7.6	The InsurTech community and other third party service providers
It is worth noting that attention is needed not just to the technical side, but also to the business and politics of an industry wide API initiative. Undoubtedly, challenges will vary by geography; regulatory regimes, political and commercial interests. All may vie to influence the shape of the proposed initiative.
Change will probably be more forcefully driven by the cooperation of both upstarts and Internet giants (a notable example is China’s first online insurance agency involving Alibaba Group, PingAn Insurance Company and Tencent investing in ZohngAn Insurance Agency ). 
Some countries have exhibited more willingness than others to experiment with innovative new products and services providing superior opportunities for Insurtech startups. Emerging economies with a growing middle class and low insurance penetration rates may present exceptional opportunities over more mature economies. Some are proactively encouraging InsurTech ecosystems, including India, Singapore, Hong Kong, UAE and many others. Startups must examine closely those ecosystems. Less proactive countries may find themselves at a developmental disadvantage over time.
Investors and developers alike interested in exploring business opportunities in developing countries, will need to rely on evidence-based assessment (through utilizing local expertise, commissioning research, surveys and polls) of customer needs and demands despite what may typically be data poor environments.
Although the digitally savvy demographics have behavioral preferences that make them more likely to become FinTech users , InsurTech businesses need to gain deep understanding of their customer segments, diagnosing how different demographics, such as age, gender and income, respond to their services.
Conversely, InsurTech developers should avoid the exclusion of low income segments and the less tech savvy customers by providing solutions that unlock access to households of all income levels and tech preferences.
Other opportunities may be unearthed in insurance-adjacent sectors as customers get acquainted with insurance services that are increasingly blended-in with other sectors. Such approach can overcome traction problems that startups are usually beset with. Banks, as an example, could help new businesses overcome the substantial problems involved in building a large customer base, an aspect that provides insurers with a substantial advantage over startups.
As open insurance APIs and architectures proliferate, technology innovators must also ensure that policyholders are fairly treated and appropriately protected when the implications of certain innovations and technologies are uncertain.
This initiative allows InsurTechs, developers and those wishing to tap into the prospects that may arise the opportunity to partake in the formulation of the API standard, App review processes, discuss security concerns and recommend new technologies. Through active participation at working group and institute levels, input from established businesses, startups and InsurTech hubs is encouraged.
And while FinTech may target the financially literate, it may also have a role 
to  play  in  improving  financial  literacy
And while FinTech may target the financially literate, it may also have a role 
to  play  in  improving  financial  literacy
And while FinTech may target the financially literate, it may also have a role 
to  play  in  improving  financial  literacy
And while FinTech may target the financially literate, it may also have a role 
to  play  in  improving  financial  literacy

 

















<span>About the author</span></br>
<span>Fouad Husseini, FCII, BEng.</span></br>
<span>Author of the ‘The Insurance Field Book’, ISBN: 978-1389362477.</span></br>
<span>https://www.linkedin.com/in/fouad-husseini-acii-beng-ba22a08/</span></br>


<span>The Open Insurance Initiative (OPIN)</span></br>
<span>https://openinsurance.io</span></br>
<span>https://www.linkedin.com/company/the-open-insurance-initiative-opin/</span></br>
<span>https://github.com/OpenInsurance/whitepaper/blob/master/README.md </span></br>
<span>Copyright © 2018. The Open Insurance Initiative. All rights reserved.</span>
</p>
