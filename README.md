STATE_ELECTION_MANAGEMENT_SYSTEM

Introduction: 
This is a software project, which involves development of a web-based application namely State Election Management System (SEMS). SEMS consists of different modules like Revision & Generation of Photo Electoral Roll, Counting & Results, Nomination & Withdrawal of candidates, Ballot Paper Generation, Randomization of EVMs & Polling Personnels, Poll-Day Monitoring etc. 
This web application is intended for the use of the State Election Commission, Andaman & Nicobar Islands and other govt. stakeholders for conduct of Panchayat & Municipal Council Elections (both General and Bye Elections). 

Scope of the Project: 
Though the SEMS consists of many different modules, the scope of this project will be confined to the following modules only: -
1.	Revision & Generation of Photo Electoral Roll (Voter List)
2.	Ballot Paper Generation
3.	Counting & Results 

Brief about the modules and their objectives:
1.	Revision & Generation of Photo Electoral Roll (Voter List)

Before election, the Electoral Roll (Voter List) is revised as per the schedule ordered by the State Election Commission. 
At first, the latest published Photo Electoral Roll pertaining to Andaman & Nicobar Islands Parliamentary Constituency is shared by the Election Commission of India in softcopy to the State Election Commission. Thereafter, necessary modifications like removing of electors of tribal areas, reserved forest areas, defence areas, mapping of electors to respective Panchayat and Municipal Polling Stations as per their place of residence etc are carried out at the level of different Asst. Electoral Registration Officers (AEROs) concerned and a Draft Electoral Roll is published.
Claims and Objections are then sought from eligible citizens in the prescribed format (Form-2) which is processed after due field verification and the forms are then accordingly either accepted or rejected and after incorporating all accepted claims and objections, a final Electoral Roll is generated and published.
Presently, preparation of Draft Electoral Roll, receiving of claims and objections from the general public is carried out manually and the manual form so received are then processed manually by different level of officers. Only the accepted forms are then digitized for generation of Photo Electoral Roll in pdf format. 
This module aims to computerize the entire process of generation of Electoral Roll right from the initial stage of preparation of Draft Roll to online receiving of Claims & Objections in Form-2, processing and accepting/rejecting of forms and generation of PDF Photo Electoral Roll. 
This computerization will make the entire process smoother, efficient, transparent, and trackable. The system will generate various reports such as Photo Electoral Rolls, District-Wise/Tehsil-Wise/PS-Wise Elector details, other Gender Wise, and Age wise reports etc.

2.	Counting & Results:

In the present system of vote counting, Counting Centres are set up at all tehsil headquarters for counting and publishing of results of constituencies falling under the tehsils. Counting is done in rounds. After each round, the round-wise results are manually recorded in a prescribed format by the officer concerned in the presence of candidates and his/her representative(s). 
These recorded results are later digitized by IT team in excel or other such tools and a lot of works are then required to be done by the IT team to compile results of all polling stations and generate different result analysis reports.
This module aims to computerize all the works related to counting and generation of results and its analysis reports. Provision will be provided for online feeding of results of each round of counting which will enable the display of auto refreshed trends & results on big screens and over Election Websites in a real time manner and will make it possible to generate reports immediately after the data is fed and freezed. No more manual compilation of results would be required.

3.	Ballot Paper Generation:
	After the nomination period is over and all the nominations are finalized, then pdf ballot papers are prepared for each constituency and are handed over to the concerned Returning Officers. The pdf copy is then used at the Printing Press to print required quantities of ballot papers. These works are done in a highly secured manner.
	Presently pdf ballot papers are prepared by using a standalone single user MS Access application which lacks many required flexibilities and being a single user application, many Returning Officers are required to keep on waiting outside the premises late night for their turn.
	Developing a web-based solution with all required flexibilities will bring a drastic change in terms of ease of ballot preparation, timely preparation, and multiuser environment.
	Apart from pdf ballot paper, large sized list of contesting candidates to be pasted in front of polling stations can also be generated from the application.

Technology proposed to be Used:	 Asp.Net Core 8.0 with C# Programming Language & SQL Server Database.
