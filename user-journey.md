# Content

*   [User Profiles](#user-profiles)
*   [Epics](#epics)
*   [User Stories](#user-stories)
*   [Open Questions](#open-questions)
*   [Out-of-projectscope](#out-of-projectscope)

* * *
Back to [README](./README.md)
* * *
## User Profiles
* * *

#### Ute

All persons who want to receive donations for a project and register, verify and put up a project for voting for it.

#### Peter

All people who want to donate and vote for projects.

#### DAO

The DAO consists of all donors (Peters) and is a decentralized autonomous organization that controls which projects come to the vote, how the voting is done and how the donations are distributed.

## Epics
* * *

| **#** | **Epic** | **Description** |
| --- | --- | --- |
|1 | Visit website | The website has a landing page and a donor role can be selected. |
| 2 | Donate | All processes to be able to make a donation. |
| 3 | Donation Receipt | The process of issuing and sending the donation receipt. |
| 4 | Voting | All processes to be able to vote for a project. |
| 5 | Project Vote | All processes to spend the donation amount according to the vote. |
| 6 | Submit Project | Small-State-Check and enter project information. |
| 7 | Review and Create Project | All processes to add a project to the reconciliation process. |
| 8 | Create Project Account | All processes to create an own project account for receiving donations. |

## User Stories
* * *

| **#** | **User Story Titel** | **User Story** | **Acceptance Criteria** | **Status** |
| --- | --- | --- | --- | --- |
| **1.01** | Home (Donate/Create Project) | As Peter or Ute, I would like to be shown a start page to continue. | 1.  The page is accessible.<br><br>2.  When accessing the page, the selection of the role should be obviously visible. | in progress |
| **1.02** | Select donor role | As Peter or Ute, I would like to be able to select my role to be redirected to the appropriate page. | 1.  The roles should obviously be connected to the two functions "Be a donor" and "Find a donor".<br> <br>2. After clicking on a button, I am redirected to the respective page. | in progress |
| **1.03** | View account information | As Peter, I would like to see information like wether I have already made a donation, for which projects I voted and how much I donated | to be defined | in progress |
| **2.01** | Create Wallet | As Peter I would like to have the steps explained how to set up and deposit my wallet. | to be defined | todo |
| **2.02** | Click Donate Button | As Peter, I would like to enter my donation information and click a button to make my donation. | 1.  There is a form for entering all the necessary information.<br>    <br>2.  There is a button to submit the information.<br>    <br>3.  When the button is pressed, a success message for my donation is displayed on the page. | in progress |
| **2.03** | Transfer money | As a Peter, I want my money to be transferred and I get a notification to complete my donation. | 1.  The amount to be donated is debited from the donor wallet and posted to the smart contract.<br>    <br>2.  A message about the successful transaction will appear. | in progress |
| **2.04** | Become a member of the DAO | As Peter, I would like to become a member of the DAO in order to participate in votes. | 1. will be informed about upcoming votes in the DAO.<br>    <br>2. it is possible to vote in the DAO. | in progress |
| **2.05** | Receive token | As Peter, I would like to receive a token to cast my vote. | 1. a token is credited after successful donation.<br> <br>2. the token enables voting in the DAO. | todo |
| **3.01** | Issue donation receipt | As a DAO, I would like to issue a donation receipt to recognize the donation for tax purposes and to motivate donors. | 1. A donation receipt will be issued. | todo |
| **3.02** | Send donation receipt | As a DAO, I would like to send a donation receipt to provide to Peter. | 1. The donation receipt will be sent to donors. | todo |
| **4.01** | Project overview of all active projects | As Peter I would like to have all projects displayed to be able to select a project for my vote. | 1. After the transaction of the donation all available projects are displayed with project title, picture, description text and donation goal. | in progress |
| **4.02** | Voting | As Peter, I would like to be able to select a project to cast my vote for. | 1. clicking on "Select project" opens a dropdown with all projects.<br>    <br>2.  By selecting a project, the dropdown closes.<br> <br>3. By clicking on "Submit", I receive a notification of votes cast.<br>    <br>4.  The first time you click "Submit", a message will appear with the project name that was selected and the query: "Are you sure?"    | todo |
| **4.03** | Donate without voting | As Peter, I would like to be able to put a check mark to abstain from voting or to trust the DAO. | 1. Next to the dropdown menu there is a check mark "donate without voting".<br>    <br>2. after clicking on "Submit" with selected check mark I will receive a notification about cast votes. | todo |
| **4.04** | View votes overview | As Peter I would like to see an overview of the votes per project so far to know if my favorite project could win. | to be defined | todo |
| **5.01** | Quarterly notification comes in | As Peter I would like to receive a notification when a new quarterly donation period starts, to see which project has won and to know that a new period with new projects starts. | 1. With the beginning of the new donation period I will receive a notification with all the necessary information about it. | todo |
| **5.02** | Select project with the most votes | As Peter I would like to know according to which principle the winning project will be determined in order to be able to cast my vote accordingly. | After the end of the voting period, the project with the most votes in the past donation period will be determined as the winner by "Winner takes it all". | todo |
| **5.03** | Transfer money to project | As a DAO, I would like to transfer the donated money when the winning project is chosen to pay out the donations. | 1. The amount on the Smart Contract at the end of the donation period will be paid to the wallet of the person with the project with the most votes. | todo |
| **5.04** | Announce successful project | As Peter or Ute I would like to receive a notification which project has won the vote. | 1. At the end of the donation period all participants (no matter which role) will receive a notification about the voting result. | todo |
| **5.05** | Start new donation quarter | As a DAO, I would like to start a new donation period after the end of a donation period with the projects registered until then to collect new donations. | 1. After the end of a donation period, a new donation period is started.<br>    <br>2.  All projects registered until then will be part of the new period | todo |
| **6.01** | Smallstate list | As Ute, I would like to select my smallstate from a list of all smallstates in order to be able to create a project. | 1. After selecting the role "Search donors", you will be asked to select the smallstate.<br>    <br>2.  Clicking on "Select Smallstate" will display a searchable drop down list of all smallstates.<br> <br>3. A smallstate is selected and after clicking on "Next" I am taken to the "Enter Project Information" page. | done |
| **6.02** | Entering the project information | As Ute I want to enter my project information to be able to create a project. | 1. A form with input fields for all necessary information is displayed.<br>    <br>2.  If not all fields are filled, clicking on "Ok" will prompt for filling all fields.<br> <br>3. After clicking on "Ok" with all fields filled, information will be transferred to backend and informed about the further procedure. | done |
| **6.03** | View account information | As Ute, I would like to see wether I have already registered a project and the status of my projetcs | to be defined | in progress |
| **7.01** | Register project | As DAO I want to register a project with its information to be able to verify it. | 1. a new project will be created and all information will be saved. | todo |
| **7.02** | Verify Ute | As a DAO, I would like to be able to verify Ute to avoid abuse. | to be defined | todo |
| **7.03** | Verify project | As DAO I want to be able to verify a new project to avoid misuse. | to be defined | todo |
| **7.04** | Voting on acceptance of a project | As a DAO, I would like to vote on the acceptance of a project to ensure its eligibility. | 1. There will be a vote on which projects to include in the ballot before the start of a new donation period. | tpdo |
| **7.05** | Generate project keys (address) | As a DAO I would like to generate a key or an address for a new project to enable vote collection and donation transfer. | With the creation of a new project a public key is generated as address for vote collection and donation transfer. | todo |
| **7.06** | Send message to Ute | As DAO I would like to send a message to Ute to let her know if and with which address her project has been deposited for the next voting. | 1. The creating person is continuously informed about the acceptance process of her project. | todo |
| **8.01** | Accept project account | As Ute, I would like to accept a project account in order to be able to manage it. | 1. the project creator has the possibility to link the project account with his own account.<br>    <br>2. to be defined  | todo |
| **8.02** | Create Wallet | As Ute I would like to have the steps explained how to set up and deposit my wallet. | to be defined | todo |
| **8.03** | Deposit Wallet | As Ute I would like to deposit a wallet to receive donations. | 1. a wallet can be deposited to transfer donations from the project address to the private wallet. | todo |
| **8.04** | Presentation of the own donation impact | As Ute, I would like to present my own donation impact in order to transparently solicit votes. | 1. description text and photos can be added, removed or changed to a project.<br> <br>2. click on "Save" to save the changes. | todo |

## Open Questions
* * *

| **Question** | **Answer** | **Date of Answer** |
| --- | --- | --- |
| What happens to the projects that did not win? Are they automatically reinstated in the next donation period? | | |
| Can I only vote in the donation period in which I also donated? | | |
| Do I have to have donated in a donation period in order to vote in that donation period? Or do I have the right to vote with a one-time donation in every donation period (regardless if I donated = tokens are valid forever)? | | |
| Can everyone see the project overview, or only those who have already voted? | | |
| How does the verification of Ute work? | | |
| How does the verification of projects work? | | |
| How does it work with Private Key of the project (Story 8.01)? |     |     |

## Out-of-projectscope
* * *

*   Payment with cryptocurrency in Small States cf. [confluence](https://htw-berlin-bui.atlassian.net/wiki/spaces/SEAL/pages/5931013)
    

*   Definition Small States and process of submission of projects