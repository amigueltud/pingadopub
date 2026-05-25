# Public - Bachelor's Thesis in Computer Science

# Proposal of an Architecture Based on E-Contracting to Charge by Cryptocurrencies On-demand Content Consumption

This is a public version of the work carried out for the production of the Bachelor's thesis in computer science at the Mackenzie Presbyterian Uniersity of an architecture based on e-contracting to charge by cryptocurrencies on-demand content consumption and defended in June 2018 by **Andre Miguel**.

### Auhtor, Supervisor
André Augusto Miguel (_`amigueltud (at) gmail.com`_), Ana Claudia Rossi (_`ana.rossi (at) mackenzie.br`_)

## Abstract

This article presents an architecture of electronic contracting to support
a system of provisioning streaming content and charge the consumption by
cryptocurrency payments, altogether with the framework of pricing over that
content. The context is the on demand video streaming rental. Currently companies
and amateur producers provide videos and charge their customers via
monthly payment or single rental per video; however, neither the possibility
for charging on demand, nor using cryptocurrencies for this purpose has being
explored. The architecture presented comprises the formatting of electronic
contracts and the price composition of the content being provided on demand to
be charged by cryptocurrency payments via blockchain distributed system.

## Introduction

The field of entertainment and the search for knowledge have always been motivated to
seek content in diverse sources. Nowadays the production of content in the internet is
abundant and its authors can host it either in specialized providers, such as YouTube,
SoundCloud, Spotify among others, or even themselves to own and transmit over their
private internet access. However, the remuneration for the consumption of this content
to the authors usually falls short of what they expected. The remuneration for the author
is normally determined by the host company. Hiring content for consumption is usually
not a formal process; it is often enough for the consumers to access the website where the
content is hosted, without being necessary to identify themselves. In this scenario, neither
the author nor the customer has influence on how much the author will receive from the
customer enjoying his or her work.

Cryptocurrencies provide a high level of reliability, security and publicity, thanks
to very well-developed mathematical constraints and algorithms that prevent fraud in the
system [Xu et al. 2017] 8888888. Therefore, as a means to reduce costs, universalize access and
speed up the transfer of values, it is observed that the use of cryptocurrencies has the
potential to be studied as an analogous and substitute method to bank transfers, in the
case of consumption of content on demand. The transfer of values can be achieved by
the integration with a blockchain distributed system network. However, trading is not just
about transferring values. The contracting and other definitions of the agreement are an
essential aspect to be considered in order to achieve the negotiation.

Therefore, to give control of the price charged by the media consumption to the
author, to streamline the contracting process and to facilitate the transfer of values, an
architecture is proposed that employs structures according to the electronic contracting
[Angelov 2006] 88888 and pricing of Software-as-Service [Wu et al. 2014] 88888 over the content.
The aim is to streamline the pricing and contracting of content on demand, to facilitate the
provisioning process and to integrate transfer of values into the process [Xu et al. 2016] 88888.

## Theoretical Framework

The present study works with the framework of electronic contract elaboration of
[Angelov 2006] 88888 and combines its paradigms to come into an adequate representation of
the contractual relationships on the supplying of content on demand; additionally, the
three-tier framework for software-as-a-service pricing of [Wu et al. 2014] 88888 was used to
evaluate the best type of pricing. This is the basis on which it was studied the proposition
of an architecture to control the supply of media on demand and how the consumption of
the content can be charged efficiently.

Next, it was studied how the monetary values can be transferred in a more independent
form of regional and regulatory restrictions, through the use of channels of
distributed systems type blockchain network and its cryptocurrencies [Xu et al. 2016] 88888.

Software system was produced as proof of concept of the employment of e-contracting
and pricing frameworks, which allowed to subsidize the proposed architecture
to effectively control contracting, supply of content on demand, and contract termination.
The form to charge consumption that was intended to demonstrate its feasibility is of
cryptocurrencies payments. Therefore, the formal conclusion of electronic contracts, the
form of appropriate pricing and the subsequent transfer of monetary resources through
cryptocurrency channels are the purpose of this research.

### Electronic Contracting

Contract is an instrument of obligations and rights in which both the parties contractor and
contracted agree. In current business environments, with new performance parameters
being demanded from companies, the dynamics of closing agreements has required more
and more agility and speed, so it is not appropriate to neglect any contractual aspect. Thus,
electronic contracting was introduced [Angelov 2006] 88888 as a concept that reduces cost, time
and complexity, as opposed to paper contracts [Angelov and Grefen 2014] 88888. E-contracts
are divided into shallow e-contracting, in which an e-mail exchange is already enough,
and deep e-contracting, which will be the subject of study of this research. The definition
of deep e-contracting [Angelov and Grefen 2014] 888888 is: “_(1) Information technology is used
to aid the contracting process; (2) contracts have digital representation; (3) the level of
automation introduced by the use of information technology either leads to the creation of
new business processes in the organization or significantly changes existing processes_”.

### Pricing

Software-as-a-Service (SaaS) is offered such as it were a service and is hosted and accessed
across the internet. SaaS is at same time both a product and an outsourced service,
which means that both infrastructure and management are operated by the supplier
[Wu et al. 2014] 88888. It is similar to a leasing, but, in the end, the contractor does not have
the product for himself. Likewise is the provision of media content on demand, in which,
in the end, the customer will not keep the media with him, he will only have enjoyed the
content. The proposed three-tier pricing was studied to understand how to be employed
in the research setting up.

### Blockchain

Blockchain is a distributed system closed on itself; nothing that is strange to the system
can enter the execution environment. The operation takes place in a decentralized and
transactional way and the data is shared by a network of untrusted participating nodes.
More generally, blockchain is a public domain ledger, maintained by all nodes of the cryptocurrency
network, which agree on the states of their operations [Xu et al. 2016] 88888. Transactions
in the blockchain network are validated by defined rules and are encapsulated in
chained blocks, one after another in a process that is called “mining” [Xu et al. 2017] 88888.

### Cryptocurrency

Cryptocurrency is a digital currency based on a point-to-point network and cryptographic
tools and is inherently independent of a central authority. This virtual money can be
transferred between users, directly, without the need of a constituted authority to authorize
the transaction [Xu et al. 2016] 88888. Cryptocurrencies are the main product created by the
first generation of blockchain systems [Xu et al. 2017] 88888. Cryptocurrencies do not need to
be notarized, that is, they do not have a holder who owns their property; they are a kind
of bearer title. The transactions, in turn, are registered and, similarly, notarized in the
blockchain network.

## Research Methodology

This work was based on applied research, with a qualitative approach, which sought to
understand how to circumvent the problem of dissatisfaction with the amount paid to
content producers by the consumption of their work. To do so, it was studied how to
employ the electronic contracting and pricing structures of SaaS, as well as to perform
electronic transfer of monetary units, to propose an architecture that would satisfy the
need to formal contracting the media consumption and subsequent payment. In addition,
with the bibliographical survey carried out, it was possible to gather material that would
subsidize the elaboration of the proposal of an architecture that could be attested by the
development of software as a proof of concept artifact.

The bibliography explored began by studying electronic contracting. In this regard,
the research of [Angelov 2006] 88888 came to support all development of the proposed
architecture, since it is the formal contract that will establish the rights and obligations
between the parties. The concept groups and the paradigms of e-contracting were studied.

Next, the three levels of SaaS pricing framework from [Wu et al. 2014] 88888 were studied,
since it was observed that the price should be properly defined to complete the e-contract
formatting. The analysis of price formation is given by orientation, in level 1 and
goes to categories, in level 2 and its specific components, in level 3.

Having completed the elaboration of the domain entities derived from the studies
on e-contracting and pricing (figure 2 and figure 3), it was defined how the transfer
of values should be carried out. It was chosen to transfer values in cryptocurrencies
by using a blockchain network with the element “validation oracle”, as presented by
[Xu et al. 2016] 888888.

As a result, the proposed architecture could be built and had the proper proof of
concept developed in software that integrated the entire bibliographic reference.

