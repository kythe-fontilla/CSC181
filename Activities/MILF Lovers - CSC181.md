# **Team Brainstorming and Preliminary Project Proposal**

# **Team Information**

\- Team name: Anti-Kamote Gang  
\- Working arrangement: Personal computers  
\- Coordination method: Online Google Meet call, shared document

| Member | GitHub username | Personal CSC181 repository |
| ----- | :---: | ----- |
| Kate Mikaela R. Dagohoy | mxikai | https\://github.com/mxikai/csc181 |
| Joash S. Casiño | joashcasino-sketch | https\://github.com/joashcasino-sketch/csc181 |
| Kythe Florence P. Fontilla | kythe-fontilla | https\://github.com/kythe-fontilla/CSC181 |
| Kenneth Jerome C. Gloria | Kenji7676 | https\://github.com/Kenji7676/csc181 |

### **1\. Brainstorming Record** 

| Member | Problem or inconvenience | Who experiences it? | Current approach | Basis of the idea |  
|---|---|---|---|---|  
| Casiño | Working students at MSU-IIT struggle to balance academic and work commitments since communication channels are spread across multiple platforms. Manually checking each app to track incoming deadlines results to missed tasks, cramming, and lesser output quality. | Working students | Manually checking multiple separate communication and project platforms (Google Classroom, MICA, Slack, Notion, Messenger) to track incoming deadlines. | Experience |  
| Gloria | Long physical queue lines and overcrowding in the office, wasting students’ time and academic responsibilities. | Students | Physically visiting the registrar's office and waiting in long, unmanaged on-site lines to handle document requests. | Observation |  
| Gloria | Lines get so long during the attendance checking of every event that it becomes a long wait for most students. | Students/Organizers | Standing in line at the venue entrance to manually write down details on paper sign-in sheets or typing in sheets. | Experience |  
| Gloria | Dormers/Students aren’t sure where the best budget-friendly meals and \*karinderyas\* are around IIT | Students/Dormers | Wandering around the neighborhood aimlessly, relying on word-of-mouth, or sticking to the same 1–2 nearby spots out of habit. | Experience |  
| Fontilla | Requirement guidelines are unclear and oftentimes scattered, leading to missed paperwork, back-and-forth re-submissions, and delayed event approvals right before target event dates. | Student Organizations | Inquiring at the OSDS office in person, asking senior officers, or digging through old files to look for the paperwork needed. | Experience |  
| Fontilla | Public Google Sheets lack privacy. Anyone can accidentally or intentionally edit, delete, or leak students' personal data. | Students/Staff | Sifting through public, shared Google Sheets where scholarship listings and student application details are stored. | Observation |  
| Fontilla | Job openings are constantly open but often do not specify if they are student-friendly. | Students/Employers | Looking through Facebook groups, relying on word-of-mouth. | Experience |  
| Dagohoy | Posts being buried under various other posts, missing items get scattered across different locations and sometimes isn’t even reported because they don’t know where to surrender it or who to contact. | Students/Staff/Employees | Posting on Facebook groups, Messenger group chats, or leaving items at guard posts. | Observation |  
| Dagohoy | There is no singular space to know if a venue has been booked at a glance. | Student Organizations/Organizers/Faculty | Going through different colleges and offices across the university | Experience |  
| Dagohoy | Navigating through buildings and rooms throughout MSU-IIT can be hard and confusing at times. | Freshmen/Students/Visitors | Blindly navigating or having to ask around | Observation |

### **2\. Candidate Comparison and Selection**

\#\#\# Three shortlisted problems

| Candidate problem | Why it matters | Feasibility concerns | Access to potential stakeholders |  
|---|---|---|---|  
| OASG Scholarship App | Serves as a centralized portal for real-time updates on all available scholarships partnered with MSU-IIT; Addresses existing privacy vulnerabilities by replacing publicly accessible files with secure account access; Streamlines the application process by enabling students to submit required documents directly through the portal, similar to Common App. | Establishing reliable API/data-sharing connections with external scholarship grantors; Building and maintaining a secure, scalable server-client infrastructure. | Students, Scholarship Grantors, OASG |  
| Part-Time Student Hiring App | Upgrades informal Facebook groups into a structured, dedicated platform designed specifically for student employment; Creates a centralized space connecting local employers with students actively seeking part-time jobs to support their education. | Sustaining continuous user engagement and adoption from both students and local employers. | Students, Local Employers and Businesses |  
| Lost & Found App | Establishes a single, organized dashboard to post missing items, log last-seen locations, provide contact info, and track claim status; Utilizes an intuitive marketplace-style layout for easily browsing lost and found items; Can be integrated directly into the existing My.IIT web portal for seamless access. | Navigating university bureaucracy and administrative approvals for official integration into the existing MSU-IIT system. | Students, Staff, Security Personnel |

\#\#\# Selected problem

The team has unanimously selected the Lost & Found app after voting and deliberation.

\#\#\# Selection rationale

We chose the Lost & Found App because it addresses a problem students and staff across campus deal with regularly, and we found that the simpler the project, the better. Its focused scope fits with the available timeframe the team has to work with, and we can run it on a standalone demo server without fully integrating it into My.IIT yet, which keeps it realistic for a single semester. MSU-IIT students, staff, and security personnel, our main stakeholders, are also easy for us to reach, so we can gather feedback and test the app throughout development. The scholarship and part-time job portals were set aside because they relied heavily on outside partners like grantors and local employers. Coordinating with them would have added bureaucratic hurdles that didn’t fit our timeline or our readiness.

### **3\. Preliminary Project Proposal**

\#\#\# Working project title

MSU-IIT Lost and Found (MILF)

\#\#\# Problem statement

Whenever MSU-IIT constituents lose valuable items, they often resort to posting on community groups in Facebook or going through the hassle of approaching the Security and Investigation Division (SID), the respective office in-charge of handling lost and found items. However, posting online does not guarantee that the concerned individuals can see the post, and it also has the risk of getting buried by more recent posts. The other option of going to the SID office takes quite a bit of time and effort and involves a lengthy process of verifying ownership claims. This project aims to streamline the process of reconnecting lost items to their respective owners, reducing the time, effort, and resources needed to accomplish such. To achieve this, we must first need to verify the constituents’ perception on the currently available means of relocating lost items in terms of convenience, ease-of-use, and overall efficacy.

\#\#\# Proposed solution

MSU-IIT Lost & Found (MILF) is a centralized web app where students and staff can post lost or found items, log where an item was last seen, share contact details, and track whether it has been claimed. Instead of relying on scattered chat groups or dropping items off at different campus offices, users get one searchable dashboard with a marketplace-style layout that makes browsing items quick and familiar. We plan to run it as a standalone demo server for now, but it is designed so it can later be integrated into the My.IIT portal for seamless access. By making every item’s status, location, and point of contact easy to find, MILF takes the guesswork out of recovering lost belongings across campus.

### **4\. Stakeholder List**

| Stakeholder role/group | Relationship to the project | Likely need or concern | Question to ask | Possible consultation method |  
|---|---|---|---|---|  
| Students | Primary user that reports, claims, and search items | Privacy of their personal info, especially for IDs. Someone claiming their item and the app being complicated to use | 1\. What do you usually do when you lose something at school? 2\. How long does it take you to get an item back, if at all? 3\. What details would you want to see in a listing before claiming an item? 4\. Would you be comfortable with an item photo being in public? 5\. What would make you actually use this app instead of the current method available?| Online survey |  
| Teachers and other school staff | User who post found items and search for their own lost ones | Extra work. Being responsible for an item if a claim goes wrong | 1\. What do you currently do when you find a lost item? 2\. How much time would you be willing to spend posting one item? 3\. Should you hand the item to the admin, or keep it until it is claimed? 4\. How would you like to be notified if something you lost is found? 5\. Are there items you would not want to post publicly, like IDs or wallets? | Survey or informal interviews |  
| Security Personnel | Manages listings, verifies claims, and returns items | Too many items piling up. Fake or duplicate claims. Poor-quality post, vague and unclear description | 1\. How do you currently record and store lost items? 2\. How do you verify that someone owns an item? 3\. How do you keep unclaimed items, and what happens to them afterwards? 4\. What are the most common problems you face with claims? 5\. What reports or records do you need to keep?| One-on-one interview |  
| School Administrator | Approves the system and sets policy on lost item handling | Liability if an item is wrongly released. Cost and effort of adopting a new system. Student data privacy and safety. | 1\. What policies exist on handling and releasing lost items? 2\. What reports would you want to see, and how often? 3\. What information about students can and cannot be shown in the app? 4\. Who would be allowed to register and post? 5\. What are your concerns about adopting a new system? | Formal interview |  
| Developers and IT department | Build, deploy, and maintain system | Security risks such as account abuse or exposed data | 1\. What are the security and data storage requirements? 2\. Who will maintain the system after the project is turned over? 3\. Are there tools or technologies we are required or not allowed to use? | Technical meeting |

Stakeholder-count explanation, if needed: Not Applicable

### **5\. Initial Scope** 

\#\#\# Intended users and setting

The system will be used by the MSU-IIT campus community in Iligan City. It will run as a web application that users can open on their phones or computers anywhere on campus, especially right after an item is lost or found in common areas such as classrooms, laboratories, the library, canteens, the gym, and hallways. Only users with an MSU-IIT Google account will be able to sign in.

The intended users are:

\- \*\*Owners (students, faculty, and staff who lost an item):\*\* search the listings, report a lost item, and submit a claim for an item they believe is theirs.  
\- \*\*Finders (students, faculty, and staff who found an item):\*\* post a found item with a photo, a short description, and where and when it was found.  
\- \*\*Temporary handlers (campus security and facilities personnel):\*\* receive surrendered items, log them in the system, and keep them safe until they are claimed or turned over to the Lost and Found office.  
\- \*\*Security Personnel:\*\* reviews and approves listings, verifies claims, records released items, and manages items that remain unclaimed.

Other stakeholders who are affected by the system but will not use it daily:

\- \*\*School administration:\*\* approves the system and sets the policies on releasing items and protecting student information.  
\- \*\*IT department and developers:\*\* host, secure, and maintain the system after the project is turned over.

\#\#\# In-scope capabilities

1\. \*\*Sign in with an MSU-IIT Google account:\*\* Users log in using their institutional Gmail, so only members of the campus community can post, search, or claim items.  
2\. \*\*Post a lost or found item:\*\* Users create a listing with a photo, item category, short description, and the location and date it was lost or found.  
3\. \*\*Search and filter listings:\*\* Users browse lost and found items and narrow the results by category, location, date, or keyword.  
4\. \*\*Submit and track a claim:\*\* Owners send a claim on a found item by answering identifying details (such as color, contents, or distinguishing marks), then check whether the claim is pending, approved, or rejected.  
5\. \*\*Manage listings and verify claims:\*\* The Lost and Found administrator and campus security approve or remove listings, review claims, mark items as released, and flag items that remain unclaimed.

\#\#\# Out-of-scope capabilities

1\. \*\*In-app messaging and notifications:\*\* The system will not include chat between finders and owners, or email, SMS, and push notifications. Users will check claim status inside the app, and item handover will happen in person at the Lost and Found office or campus security.  
2\. \*\*Custom UI themes:\*\* Dark mode, color theme options, and other appearance settings will not be built. The app will use one consistent design.  
3\. \*\*Third-party integrations beyond sign-in:\*\* Apart from MSU-IIT Google sign-in, the system will not connect to external services such as social media sharing, the university student information system, or maps. This may be revisited in a later version.  
4\. \*\*Native mobile apps:\*\* No separate Android or iOS app will be developed. Users will access the system through a web browser on their phones or computers.  
5\. \*\*Automatic item matching:\*\* The system will not use image recognition or AI to match lost reports with found items. Users and the administrator will search and compare listings manually.

\#\#\# Expected deliverables

\*\*Working Prototype\*\* A web-based lost and found app where users can post lost or found items, search listings, and submit claims, and an admin can verify claims and update item status.  
\*\*Documentation\*\* Requirements and user roles, basic design system (use cases, wireframes) and short user guide.  
\*\*Testing evidence\*\* A test case table covering the main features (posting, searching, claiming, role-based access), screenshots of test runs, and feedback from a small number of students/staff testers.

\#\#\# Constraints

| Constraint | Effect on the project | How the team will respond |  
|---|---|---|  
| Limited time (one sementer) | Not every feature can be built, tested, and documented, so advanced features may not fit | Build a minimal core first (post, search, claim, admin approval). Treat everything else as stretch goals and set weekly milestone |  
| Small team with limited experience | The team may new to some tools such as authentication which slows deployment | Pick a familiar tech stack, divide work by strength, and hold short check-ins |  
| Data privacy concerns | The app handles photos and personal details, and IDs or student information can’t be exposed carelessly | Collect minimal personal data, use only test or sample data, restrict sensitive items to admin view |  
| No budget for paid services | Paid hosting, SMS, or email services are off the table, and free tiers have storage and usage limitations | Use free hosting and free-tier tools, limit photo sizes, and skip paid integration | 

\#\#\# Assumptions and dependencies

| Assumption or dependency | Why it matters | How to check or address it |  
|---|---|---|  
| MSU-IIT Google accounts for sign-in | Sign-in limits access to the campus community specifically, and it adds trust to the users knowing they are students/staff from the institution | Test Google sign-in early in the semester using team members’ institutional accounts. If the university domain blocks third-party apps, ask the IT department to allow it, or fall back to a simple email-and-password login restricted to @g.msuiit.edu.ph addresses for the demo |  
| Free-hosting and free-tier tools for the prototype | There is no budget, and the app handles photos, which can quickly use up free storage limits | Estimate storage needs from the expected number of test listings, set a photo size limit, and trial the chosen free host in Week 1-2. If limits are hit, compress images or switch to another free provider |

\#\#\# Success indicators

| Success indicator | Proposed evaluation method |  
|---|---|  
| Users being able to post a lost or found item, search listings, and submit a claim quickly and without help | Run a short usability test with 5-10 MSU-IIT students and staff, who each perform these three tasks on the demo server while the team records whether they finish each one and how long it takes. Then, testers answer a brief survey rating convenience and ease of use. |  
| The claim process is faster and simpler than the current approach of searching through Facebook posts or walking into SID | Have testers and a team member playing the admin role, using test data,  go through a sample claim from posting to verification to marked as release, and record the number of steps and time taken. Compare this against testers’ own accounts of how long the current process takes, collected through the same survey. |

### **6\. Review and Next Steps** 

\#\#\# Change made after reviewing the proposal

\- Before review: The initial idea is a tracking system that records all lost and found items within the vicinity of MSU-IIT, and helps mediate the transaction between the finder and owner.  
\- After review: There needs to be measures put in place to help verify ownership claims so that lost items can rightfully be returned to their respective owners.  
\- Reason: It is imperative that we can ensure that false claims are flagged so that the system cannot just be exploited and that, as previously mentioned, items return to their rightful owners.

\#\#\# Biggest remaining risk

As mentioned above, the lack of a well-thought-out, foolproof security measure to check the authenticity of ownership claims remains the biggest risk that might affect the overall efficacy of this system since it may just serve as an exploitable means for people to claim items that aren’t their own. 

\#\#\# Three unanswered questions

1\. How can we implement security measures to verify ownership claims?  
2\. How can the system help coordinate the transaction logistics (location, date and time, etc.) between the finder and owner?  
3\. How can we effectively coordinate with the Security and Instruction Division (SID) to implement this as the go-to lost and found system for MSU-IIT constituents?

### **7\. Member Contribution Record** 

| Member | Ideas or analysis contributed | Drafting or review contribution |  
|---|---|---|  
| Kythe Florence Fontilla | Provided more than two problem ideas, engaged in discussion, and feasibility ideas during brainstorming. Drafted the Stakeholder List section, expected deliverables, and constraints. | Read and reviewed the entire document and gave approval |  
| Joash Casiño | Provided a problem idea, engaged in discussion, and feasibility ideas during brainstorming. Drafted the intended users and settings, in-scope capabilities, out-of-scope capabilities sections under Initial Scope | Read and reviewed the entire document and gave approval |  
| Kate Mikaela Dagohoy | Provided more than two problem ideas, engaged in discussion, and feasibility ideas during brainstorming. Drafted the final readable Brainstorming Record Section and Candidate Comparison and Selection Section. Also drafted the proposed solution under the Preliminary Project Proposal section, and the assumptions and dependency and success indicators under the Initial Scope section. | Read and reviewed the entire document and gave approval |  
| Kenneth Jerome Gloria | Provided more than two problem ideas, engaged in discussion, and feasibility ideas during brainstorming. Drafted the working project title and problem statement under the Preliminary Project Proposal section, and drafted the Review and Next Steps section. | Read and reviewed the entire document and gave approval |

### **8\. References**

None.

### **9\. Team AI Use Declaration**

Select one option:

\- \[ \] No generative AI tools were used by any member in preparing this submission.  
\- \[x\] One or more members used generative AI tools. Details are provided below.

| Member who used AI | Tool | Purpose and sections assisted | How output was checked or revised |  
|---|---|---|---|  
| Kythe Florence Fontilla | Claude (Anthropic) | Brainstorming ideas for relevant stakeholders and prototyping | Editing and restructuring  
| Joash Casiño | Claude (Anthropic) | Reviewing ideas for the Initial Scope section | Checking if there are any ideas overlooked   
| Kate Mikaela Dagohoy | Claude (Anthropic) | Brainstorming Record | To assist in the readability of the ideas and notes |

\#\#\# Main prompts or interaction summary

Main prompt: Refine the answer on the intended users and setting. Refer to the PDF I shared." (Do not include the placeholder brackets.) 

Main prompt:   
1\. Brainstorm features, users, and documents for the app.   
2\. Identify and narrow down stakeholders, then suggest their relationship to the project, likely needs and concerns, questions to ask, and consultation methods.   
3\. Brainstorm expected deliverables and explain what "testing evidence" means in a preliminary proposal.   
4\. Identify project constraints and how to respond to them.    
5\. Improve the readability of the informal drafts and notes.

We acknowledge that AI-generated suggestions are not evidence of actual  
stakeholder interviews, feedback, or verified community needs. We remain  
responsible for the accuracy and explainability of this submission.

### **10\. Team Confirmation**

We confirm that this document reflects our team's agreed-upon proposal.  
All members listed below reviewed the final version, and each member will  
upload the same Markdown file to their personal CSC181 repository.

| Member | Reviewed final version |  
|---|---|  
| Kythe Florence Fontilla | Yes |  
| Joash Casiño | Yes |  
| Kate Mikaela Dagohoy | Yes |  
| Kenneth Jerome Gloria | Yes |

### **Submission Checklist**

\- \[x\] Each member contributed at least two problem ideas.  
\- \[x\] Three candidate problems were compared.  
\- \[x\] The selection rationale is included.  
\- \[x\] The problem statement contains 100–150 words.  
\- \[x\] The proposed solution is included.  
\- \[x\] Relevant stakeholders and consultation questions are identified.  
\- \[x\] The scope contains 3–5 capabilities and at least three exclusions.  
\- \[x\] Constraints, assumptions, and success indicators are included.  
\- \[x\] A review change and three unanswered questions are documented.  
\- \[x\] Contributions, references, and AI use are declared.  
\- \[x\] All members reviewed the same final document.  
\- \[x\] Each member saved the file as \`activities/project-proposal.md\`.  
\- \[x\] Each member committed and pushed their copy to their personal repository.  
\- \[x\] Each member submitted their own GitHub file link through MOLE.  
