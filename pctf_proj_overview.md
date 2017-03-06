**APPENDIX A**

**Applied Research Project Definition Template**

Pan Canadian Trust Framework (PCTF) – Component Discovery Project
=================================================================

Problem Statement
-----------------

> The Pan Canadian Trust Framework (PCTF) identifies a set of proposed
> components which together should interoperate in such a way as to
> enable a trusted digital ecosystem for people, entities and things.
> This framework will be developed in alignment with the DIACC 10
> Principles for a Digital ID Ecosystem. Work is required to fully
> define the boundaries between these components and to discover how
> they could interoperate through well-defined interfaces. This project
> aims to explore and define initial experiences to perform discovery
> work leading to initial descriptions of several of the core components
> of the PCTF, namely Verified Organizations and Verified Relationships.
> Further, the user experience of an end user, be they in a citizen or a
> business person context, will be explored to ensure services which
> would want to leverage the ecosystem are readily able to and that the
> resulting user experience is simple and trusted.

1.  **Use/Test Case(s)**

> Two key user types are considered in this early work.

1.  A business user who would like to interact with government services
    in a simple, fully trusted digital manner. The business user needs

    a.  to be able to be connected to their legal entity in a trusted
        manner;

    b.  to be able to have a consolidated view of their core business
        data (e.g. legal registration data) and potentially auxiliary
        government data (e.g. permits, licences, contracts);

    c.  to be able to assign others to act on behalf of the legal
        entity, assuming they have appropriate authority to do so;

    d.  to be able to have a consolidated view of the people and things
        that have been authorized to act on behalf of the legal entity
        in some capacity and manage those relationships.

2.  A developer who, under appropriate authorities (e.g. is contracted
    by a government service provider, using public APIs, using licensed
    APIs) could create a service which leverages the PCTF components of
    the trusted digital ecosystem to deliver a digital government
    service which has a public facing component (e.g. procurement
    services, permit app, and the like). This developer needs

    a.  Application Programming Interfaces which expose, in a trusted
        manner, the key functions and objects of the PCTF components
        such that a user experience can be designed to meet the digital
        government service requirements.

> For each use case, a key target will be the initial creation of a
> sufficiently rich and robust framework of APIs to support an “App
> Challenge” at the Identity North conference in June 2017.

Potential Solution Elements
---------------------------

> For this early definition work a variety of tools and techniques will
> be deployed. For the user experience work, one design thinking
> workshop will be held with stakeholders from the DIACC community, and
> ideally, representative business users, to explore the needs of
> business users and reduce uncertainty around key flows such as the
> sign-in, personal identification, claiming of a business record, and
> management of a businesses’ digital relationships.
>
> From a technology perspective, the BC Government’s DevOps platform
> will be utilized which includes in its workflow, GitHub, Trello,
> Docker and other tools. To explore and enable the use cases, open
> technologies and technologies from DIACC members will be leveraged
> such as Verified.Me, the Province of BCs business data, Hyperledger,
> Node-Red, Node.JS, OpenAPI (Swagger) and others.

1.  **Constraints**

> Work will be conducted within the legal context of the DIACC
> membership. No data will be publically released that is not already
> officially open, public data. All code developed in the context of
> this project will be done under the Apache 2.0 Licence.

1.  **Questions**

> Key questions this project aims to address include:

1.  What are the data and functional representations of a verified
    person, verified organization and verified relationship?

2.  What are the trusted processes to create a verified relationship
    (between a verified person and a verified organization)?

3.  What are the key user touchpoints within a service experience to
    bring a business user and their associated business into the PCTF
    trusted digital ecosystem?

<!-- -->

1.  **Desired Benefits**

> This project will assist in the discovery of, and the reduction in
> uncertainty of, how a verified person can step into the role of a
> business owner, manage their businesses’ key data, and manage their
> businesses’ relationships as they relate to the people (and
> organizations) that are performing activities on behalf of their legal
> entity (business).
>
> The reduction of uncertainty should occur in the user experience
> domain, the specification of PCTF standards domain, and the technical
> domain as it aims to create a minimum viable instantiation of a
> trusted digital ecosystem. There will be a good deal of future work
> necessary, however it is believed that this early work will provide a
> solid foundation for further discovery efforts.

1.  **Criteria for Success**

> The key criterion for success will be the establishment of early
> versions of APIs which could support the creation of apps (web or
> mobile) which can simply make use of the PCTF components (Verified
> Person, Verified Organization, Verified Relationship) to deliver a
> simple, trusted user experience for a business user of a government
> service. Further evidence of success with be the ability to describe
> in greater detail the necessary elements of a Verified Organization
> and a Verified Relationship in terms of their data elements and
> methods.

1.  **Budget and Resource Requirements**

> The Province of British Columbia will provide funding to the DIACC for
> the delivery of a design workshop and a resource to perform
> development efforts towards the goal of the project. The total funding
> transferred to DIACC for this project will be \$75,000. The Province
> will also provide expertise for project leadership, Devops platform
> support, as well as secure computing resources for component
> development. The Province will provide access to the BC Developers
> Exchange public GitHub repository for open source deliverables.
>
> DIACC, through its members, will provide access to test environments
> for the Verified Person component, data from members as needed, as
> well as project and contract management services. DIACC will provide a
> DIACC private GitHub repository for non-public deliverables.
>
> Initial Budget
>
> Design Workshop including professional facilitation, travel for key
> stakeholders and facilities - \$20,000
>
> Web/Devops Developer for creation of APIs and demonstration Apps -
> \$55,000 (Approximately 60 days)

1.  **Time Line for Completion **

> The key deliverables, APIs to support an App Challenge at Identity
> North will need to be delivered for early June 2017. Some follow-on
> work after the conference to document and finalize deliverables in the
> GitHub environment will be complete by the end of June.
>
> A design workshop will be delivered in late March 2017 providing the
> time works for key stakeholders, otherwise it will be in April 2017.

a.  **Key Activities Timelines**

    i.  **February** – Onboard developer, develop initial specifications
        for user experience, data and functional elements, solicit input
        and initial design of workshop

    ii. **March** – Onboard design thinking facilitator, design and
        deliver design thinking workshop, early prototypes of verified
        organization API, further development of user experience in
        preparation for workshop, design of process for verified
        relationship based on a Verified.Me verified person service,
        begin organization of App Competition

    iii. **April** – Implement initial versions of APIs for Verified
        Organization and Verified Relationship, determine orchestration
        of APIs in connection with user experience designed in Design
        Thinking workshop and earlier work, implement Minimum Viable
        Product for management of business data and relationships
        leveraging APIs, identify and scope a government service app,
        continue organization of App Competition

    iv. **May** – finalize APIs for use at Identity North App
        Competition, finalize sample government service app, finalize
        App Competition

    v.  **June** – deliver App Competition and follow-up, document and
        deliver documentation and code on appropriate GitHub
        repositories

<!-- -->

1.  **Initial DIACC Proposed Member Participants **

  ---------------------------------- --------------------------------------------------------------------------------------------
  Lead DIACC Members:                > Possible Member Collaborators:
                                     
  -   Province of British Columbia   -   Government of Canada (Corporations Canada, The Office of Small and Medium Enterprises)
                                     
  -   SecureKey Technologies Inc.    -   Securefact
                                     
  -   Becker-Carrol Inc.             -   Interac
                                     
  ---------------------------------- --------------------------------------------------------------------------------------------

  ----------------------------------------------------------- -- -------------------------
  Ian Bailey, ADM                                                Joni Brennan, President
                                                                 
  Office of the CIO                                              DIACC
                                                                 
  Ministry of Technology, Innovation and Citizens’ Services      

  Date                                                           Date
  ----------------------------------------------------------- -- -------------------------


