# AidPals
A quick look into my project from Microsoft's New Technologists 2021. 

All **source code is property of Microsoft**, and cannot be made public. 

## Project Demo (with Code Previews)


https://user-images.githubusercontent.com/44450889/144820169-1d89f5f3-1201-4218-8672-61fc50e93480.mp4



**Note:** I was the top project contributor, responsible for **67.3%** of total commits. 

<img src="https://user-images.githubusercontent.com/44450889/144818312-1fb82a32-cc96-440f-a3c0-f995bce5842e.png" height="200" />

## Project Specification
## Problem statement

Many individuals, groups, and families often struggle to cover emergency costs (e.g., healthcare, funeral) and fear for their financial outlook. Users desire a personalized crowdfunding platform to contribute to and secure emergency funds (e.g., from friends and family, local communities, or even affinity groups (e.g., LGBTQ+, BIPOC)).


## Summary

Today, crowdfunding is not a reliable tool for covering emergencies, with over 90% of GoFundMe medical campaigns failing to reach their financial target. Additionally, current crowdfunding sources are impersonal and commercialized, with emphasis on storytelling. Campaigns that share an excess of personal information have shown to be the most successful, and there are concerns about the vulnerability of patients who feel pressured to subordinate their rights to privacy in order to raise money. Biases can also be roadblocks to funding—crowdfunding has been most effective in areas of high income and education, with donors coming from the same socio-economic class as those in need. This puts those in low-income and underserved communities at a significant disadvantage, and those that donate to strangers are often wary that their money is even going to the correct people/community.  

For anyone that struggles with covering emergency costs, especially those in underserved communities, AidPals is a crowdfunding meets mutual aid app that aims to remove bias and the sharing of sensitive information from crowdfunding through a community-centric model. Unlike Indiegogo, MoneyFellows, and GoFundMe, our product comes at no additional usage cost and builds communities between people who need help and those willing to offer it while protecting users' privacy. It also gives those who may need it a safety net for the future through an emergency-focused saving system inspired by rotating savings and mutual aid funds. Through AidPals, our users can comfortably ask for help from people they know or groups they can relate to.


### Customer profile

AidPal’s initial target market is Low-income individuals, groups, families, and/or affinity groups (e.g., LGBTQ+, BIPOC), as well as the individuals who want to contribute to their emergency funds. 

- **Who** – Low-income individuals, groups, families, and/or affinity groups (e.g., LGBTQ+, BIPOC) and individuals who want to contribute to their emergency funds. 
- **What** – They are living a hand-to-mouth lifestyle and fear for their financial outlook; they struggle to cover emergency costs (e.g., healthcare, funeral). 
- **Where** – In the United States 
- **Why** – They fear that they will not be able to cover emergency costs by themselves and want the tools to solve this problem. They want to be part of a local community where they feel supported financially in times of crisis. They want to donate to their local community and those in need to cover some of their emergency costs. 
- **When** – Before needing money for emergency costs as a preemptive measure. 
- **How** – After discovering the app, they would sign up, create a private group and/or join a public community and/or group. From there they can donate to other groups or communities and contribute to their own group money pool. 
 
**Persona 1:**
Alex is a trans person living in a low-income neighborhood and fears that they will not be able to cover emergency costs by themselves since they are accustomed to a hand-to-mouth lifestyle. They want to be part of a local community where they feel supported financially in times of crisis. Alex joins AidPals and searches for trans circles near them, joining their first circle. Every term, Alex contributes to a pool of money along with the people in their circle under the assumption that whenever someone has an emergency the circle will coordinate to disburse funds from the pool of money. 

In a few months Alex decides to get gender affirming healthcare and realizes they can't afford to pay for the healthcare service via their current insurance coverage. Alex submits a request to their circle, and the circle admins agree to give them money from the accumulated pool. Alex is grateful they had a safety net in their time of need and continues to contribute a set amount of money in the coming terms so they can help others in their circle in case they experience an emergency or in case Alex has another emergency in the future. 

**Persona 2:**
Rebecca heard about AidPals from her friends; remembering how her family struggled to cover her brother’s medical bills, she realizes that her family could benefit from a circle in the future. She creates a new private circle and sends her Circle ID to her family so that they can search for her circle; as Rebecca’s family send requests to join, Rebecca accepts them into the circle.  

Every month, Rebecca and her family contribute to the circle. A few months in, her uncle has a heart attack; he survives, but his insurance doesn’t cover his medical bills. Her uncle creates a request to cover the portion of his bill that he can’t afford; once his request is approved, he receives the money from the pool and is grateful that his family used AidPals to save money for emergencies. The family continues to contribute money for future emergencies. 

**Persona 3:**
John has donated to GoFundMe campaigns from time to time, but he wants to make a recurring impact on his local community. John hears about AidPals, and realizes that he can use the app to donate to local circles. When he joins the app, he searches for communities near him and sets up a recurring donation to a popular circle in his area. He is happy that he can be sure his donations are going straight to local community members in their times of need.  

## Goals

- Build a community support system – people of similar experiences or locations can depend on and support each other financially in strenuous times or when emergencies emerge.  
- Improve financial security - many low-income communities do not have a safety net that can be used to meet unanticipated expenses such as illness or major home repairs. AidPals could serve as an emergency fund to cover such unexpected expenses. 
- Remove bias in crowdfunding by creating inclusive, community-oriented spaces (circles). 
- Increase donor satisfaction - most crowdfunding apps do not take accountability in letting donors know if their contributions went into the intended goal. With AidPals, donors get to see how they helped others out. 

## Non-Goals
- Create a fully public crowdfunding platform like GoFundMe.  
- Display (or allow users to display) sensitive, private information to large public groups, including images of sick patients and constant medical updates.
- Center storytelling as a factor to crowdfunding success.  
- Allow users to request from circle pools without personal contribution. 

## In scope

- P0: A user can sign-up for the app. 
- P0: A user can join a new circle. 
- P0: A user can view a list of their circles.
- P0: A user can access a page corresponding to a circle.  
- P0: A user can view their commitments and due dates to circles. 
- P0: A user can search circles. 
- P0: A user can start/create their own circles. 
- P0: A user can access active requests in a specific circle. 
- P0: A user can access a list of their transactions in a specific circle. 
- P0: A user can view their personal transactions. 
- P0: A user can request money from a circle. 
- P0: A user can contribute money to a circle. 
- P0: A user can edit their user profile. 
- P0: A user can edit their payment information. 
- P0: A circle owner can manage a circle and approve monetary requests. 
- P1: A user can donate to an outside circle. 
- P1: A user can verify their identity in their user profile. 
- P1: A user can request to join a private circle.  
- P1: A private circle owner can approve requests to join the circle.  


## Out of scope

- A user can browse circles displayed on a map. 
- A user can zoom out on a map as circles merge into bigger bubbles. 
- A user can access nearby circles based on location. 
- A user can interact with their community through an integrated platform (i.e., Tribe) 
- A service administrator can manage circles, etc.  
- Incorporate APIs for verification and bank transfers (Payment APIs like Stripe). 


## UX

AidPals is being built as a mobile application.

This is this login screen, where users have the option to sign in with a password and a username if they have an account or press create account to create a new account. 

<img src="https://user-images.githubusercontent.com/44450889/126696552-dce8622b-8437-41e4-93a2-714d08a3c793.png" height="400" />

Once users create a new account they will be directed to a page to verify their identity by using a code sent to their phone number. If the code the user enters matches the code sent to their number, the user will be directed to the home page of the app.

<img src="https://user-images.githubusercontent.com/44450889/126697067-2b075303-0906-4a9d-ae09-8fc232014240.png" height="400" />

This is the home page. At the top users can see the circles they are in at the moment and also their upcoming commitments/obligations in their circles. Under there they can search for new circles they want to join. If they press on any of the circles they are currently in they will be taken to the page for the corresponding circle.

<img src="https://user-images.githubusercontent.com/44450889/126697177-97d19694-c361-4779-bfab-f5b4e697a7bb.png" height="400" />

This is the create circle page which allows users to create their own private or public circles.

<img src="https://user-images.githubusercontent.com/44450889/126697225-d6473f8d-386e-4972-a5e1-dd8566f510f4.png" height="400" />


This is what a circle page looks like. In this example we have picked Seattle LGBTQ+ community circle. Here users can see any active money requests and if they press my transactions tab they will be able to see all of their transactions in this circle. If the user wants to fulfil a pending request by sending money they can press on fulfil request which will take them over to the page to send money. If the user prefers to send money to the general pool and not a specific case then they can press contribute and they will be directed to a page to give money. Additionally, the user can request money by pressing request.

<img src="https://user-images.githubusercontent.com/44450889/126697281-fafd0929-0937-4589-ae6c-bef5b6ee672b.png" height="400" />

This is the request money page where the user enters the amount they need and the reason they need money. The button submits their request and takes them back to the landing page for the circle.

<img src="https://user-images.githubusercontent.com/44450889/126697313-f2e81ba8-97fe-4a52-bb70-e8b96293e1fa.png" height="400" />

This is the contribute money page where the user enters the amount they want to give and the payment recurrence model. The button deposits their money and takes them back to the landing page for the circle. Tags are available for users to donate money to smaller groups within the circle like the Trans community within the LGBTQ circle for example.

<img src="https://user-images.githubusercontent.com/44450889/126697362-008dd6e7-98fd-481f-bac1-1bdd414a3299.png" height="400" />

This is the user profile page where the user can input their personal information including a button to send a verification code to the phone number associated with their account. The other button allows users to set up preferred forms of payment. 

<img src="https://user-images.githubusercontent.com/44450889/126697418-e27eb0b0-7ed9-466f-999c-cd8273fb4e74.png" height="400" />

This is the payments page where a user can add their preferred form of payment.

<img src="https://user-images.githubusercontent.com/44450889/126697444-12faa8c0-748d-4288-8982-86b50270a5c1.png" height="400" />

Here users can enter their details of their credit/debit card to have it saved as a form of payment.

<img src="https://user-images.githubusercontent.com/44450889/126697490-57affca3-966b-4cc0-bc5c-e15c6eb54ad9.png" height="400" />

#### Circle Manager Specific Pages

The circle page for managers will look slightly different in that they will have access to all transactions within the circle and they will also have a manage button that allows them to manage requests to join a private circle and edit the settings of the circle.

<img src="https://user-images.githubusercontent.com/44450889/126697540-41256a36-768d-4f59-a36c-7846fc1511bc.png" height="400" />

Circle managers/administrators will have a page to allow them to approve and disapprove requests to join a circle in private circles. In addition, they will be able to approve and deny requests for money based on the reasoning they’re given in the request form.

<img src="https://user-images.githubusercontent.com/44450889/126697677-4ecc6c69-2f22-4e9b-8f47-2b6dd504bac3.png" height="400" />

#### Walkthrough
<img src="https://user-images.githubusercontent.com/44450889/126697731-0ee11d7f-11e0-40c6-b14c-62e8d04a88d7.png" height="400" />

## Breakdown of work

| User Story | Engineering Description | Assigned To |
|---|---|---|
| P0: A user can sign-up for the app | Functional. User data stored in database. | Beza |
| P0: A user can join a new circle. | Functional. User data stored. | Maddie |
| P0: A user can view their circles as a list. | Functional. User data stored. (Dummy Data) | Maddie |
| P0: A user can view their commitments and due dates to circles. | Functional. Data stored. (Dummy Data) | Maddie |
| P0: A user can search for/browse circles. | Functional (Dummy Data) | Maddie |
| P0: A user can start/create their own circles. | Functional. Data stored. | Beza |
| P0: A user can access circle information active requests in a specific circle. | Functional (Dummy Data) | Nahom |
| P0: A user can access a list of their transactions in a specific circle. | Functional (Dummy Data) | Nahom |
| P0: A user can request money from a circle. | UI / Request stored in database. Not connected to Payment API. | Enrique |
| P0: A user can contribute money to a circle. | “Functional.” Contribution stored in database, but no real money is used; not connected to API. | Enrique |
| P0: A user can edit their user profile. | Functional. Data stored. | Taonga |
| P0: A user can edit their payment information/ add payment methods. | Semi-functional: hard code identification of card type based on number. Not connected to a Payment API. (Dummy Data) | Taonga |
| P0: A circle owner can access circle information of all requests in a specific circle. | Functional (Dummy Data) | Nahom |
| P0: A circle owner can manage a circle and approve requests. | Functional. Data stored. | Enrique |
| P1: A user can donate to an outside circle. | “Functional.” Contribution stored in database, but no real money is used; not connected to API. | Enrique |
| P1: A user can verify their identity in their user profile/ on sign up. | Potentially functional using SMS verification. Potentially hard-coded UI. | Beza |
| P1: A user can request to join a private circle. | Functional. Data stored. | Maddie |
| P1: A private circle owner can approve requests to join the circle. | Functional. Data stored. | Maddie |

## Compete analysis

Competitors of AidPals currently include: 

- **GoFundMe:** The “most trusted” online fundraising/crowdfunding platform; for-profit and a largely used site for emergency crowdfunding. ($10B+ raised.) Made for personal fundraising. 
- **Money Fellows:** A collaborative group lending and savings platform to find and manage Money Circles (digitizes rotating savings). Mainly based in Egypt. 
- **Fundly:** A crowdfunding site with similar purposes to GoFundMe, but that better supports both individuals and organizations. 
- **Indiegogo/Kickstarter:** Crowdfunding platforms that help individuals and companies raise money for products and creative projects. Kickstarter is “all or nothing” crowdfunding while Indiegogo is not. 


From the summary of the competitive analysis, the primary strengths, weaknesses, opportunities, and threats for AidPals are:

Strengths:

- No added usage fees—all funds go to users and our self-financing model does not take away from user funds. 
- Option for personalized emergency fund request rather than posting publicly. 
- Option to crowdfund from specific communities. 
- Constantly growing pool of money in individual groups, saved for user emergencies. 

Weaknesses:

- Lack of reputation—no one knows the product initially, so it’s hard to build trust with the community. 
- Lacks better verification than competitors, harder for users to trust the product in larger circles if fraud is just as possible (there is also an opportunity here to create a more trust-able verification system). 


Opportunities:

- Growing community of local customers as well as customers in affinity groups. 
- Prevent fraudulent activities through a robust system of community building. 
- Provide a safety net for a wide range of customers in emergency conditions. 


Threats:

- One of the established crowdfunding companies could easily incorporate circle/community-based crowdfunding on their platform. This would make it difficult for our app to gain traction because the established company has already developed trust among users and has a sizable user base. 
- Failure to anticipate donor trends as their wants and expectations change over time. Donors may become disconnected if no long-term relationship with supporters is made. 
- Sluggish digital growth in some communities that may need the app. These people may be failing to keep up with the digital change. 


## Future opportunities

Community Integration

- Either a native community integration or using an external integration such as Tribe to allow Circle members to chat with one another (better facilitating community) 
- Additional features such as a friends list and the ability to add people as friends/ view their profiles 
- Connections to discussion based platforms such as Reddit to encourage people to get closer. (Also, integration with/plugging into existing platforms like LinkedIn.) 

Revenue model

- With all of the pooled money in all of the groups, this sitting money could be used to invest.
- The pooled money would go through a time without a need for it since its sole purpose is to pay for emergency costs which only occur when an emergency happens. So this time that the money isn’t being used is called sitting money.
- The individuals in groups would be incentivized to pool in more money as there would be an interest rate like a bank account, but with higher rates.
- (Like how a bank profits from investing this sitting money, we would make safe investments.)

