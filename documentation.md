# Github URL


## 1.1.1 Background

Work Experience Portal

Lockheed Martin UK (LMUK) offers work experience placements to aspiring engineers at the start of September each year. It has been requested that a website be developed to centralise the information to be delivered to students and provide a go-to for any potential queries. 

Note: some of the sections contain placeholder content as I have been unable to obtain certain documents in the current climate with colleagues working from home. 

The website contains:
 - A front page containing general/important information regarding work experience placements, as well as a news feed column. 
 - An agenda page, detailing the timetable the student will be following for their placement. 
 - A profile page, with fields to be completed by the student as a means to provide LMUK with more information regarding their application and career goals. 
 - A Frequently Asked Questions page, to provide additional means of support to students with queries, including a submission form for further questions. 
 - A digitalised workbook. The current workbook is distrbuted on paper, however, with conflicting meetings and schedules, these may not be received by students until further into the week. A digital copy is always available. 

## 1.1.2 Wire Frames

    **index.html (Homepage)**
    Desktop: ![](wireframes/homepage-desktop.png)
    Mobile: ![](wireframes/homepage-mobile.png)

    **day1.html, day2.html, day3.html, day4.html, day5.html (Agenda)**
    Desktop: ![](wireframes/agenda-desktop.png)
    Mobile: ![](wireframes/agenda-mobile.png)

    **profile.html (Profile)**
    Desktop: ![](wireframes/profile-desktop.png)
    Mobile: ![](wireframes/profile-mobile.png)

    **faqs.html (FAQs)**
    Desktop: ![](wireframes/faqs-desktop.png)
    Mobile: ![](wireframes/faqs-mobile.png)

    **workbook.html (Workbook)**
    Desktop: ![](wireframes/workbook-desktop.png)
    Mobile: ![](wireframes/workbook-mobile.png)

## 1.1.3 Colour Choices

The colour palette for the Work Experience Portal pertains to LMUK intranet site colour palettes. The prominent dark blues are characteristic of Lockheed Martin's brand, combined with the white backgrounds and black text make the data easily visible to the user. Orange accents are used to highlight objects of interest to the user.  

## 1.1.4 Accessibility

Upon completion of the site, I compared my work against the W3C accessibility standards [Easy Checks - A First Review of Web Accessibility](https://www.w3.org/WAI/test-evaluate/preliminary/) and conformed in large part to the checks. 

All of my pages are titled, concisely detailing the content of the page. 

Each image has a description alternative to support screen readers and stand in for situations where the image cannot be rendered. 

Headings for each page are hierachical to present clear structure to the reader. 

Text and background contrasts pass online contrast checker tests and these colour choices made allow for good readability of material. 

Text remains large when using smaller devices to easily express the required information to the user. 

## 1.1.5 GDPR

Personal data is exchanged from work experience students to LMUK during the process of receiving a placement, as is necessary to pass baseline security checks as well as inform LMUK of the students themselves. An additional privacy policy would have to be drafted to encompass the information flow of any personal data the student enters via the portal, and this should be placed at the footer of every page for maximum access. 

## 1.1.6 Distance Selling

The Work Experience Portal is strictly informative and does not provide a facility for users to make a purchase of any kind, thus The Consumer Contracts (Information, Cancellation and Additional Charges) Regulations 2013 is not relevant. 

## 1.1.7 Evaluation

The completed site fulfils the requirements of developing an area that allows students to obtain all the information required for their work experience placement, albeit somewhat lacking in the desired detail due to the inability to access key documents at this time to provide this. 

Initially, I began by brainstorming the required content and segregating this output into logical categories of content that would outline the page titles: homepage, agenda, profile, FAQs and workbook. 

Wireframes were then developed to describe the desired structure and feel of the pages. A key aim was to remain in-theme with other LMUK intranet layouts, though since the audience would be work experience students during placement, the most likely device to be used would be mobile, so I took a mobile-centric approach to the wireframes. The general concept was to keep the site relatively uniform and free of clutter, as to not distract from the information being provided, and make it easily interpreted and digestible. Navigation side bars to be incorporated to outline key content and separate out any key content. 

An additional step I took was to complete the wireframes with the true colour choices. This helped me to visualise the outcome of the web pages and make additional adjustments for user experience. At this stage, it became clear that the orange accenting on key areas of interest to the user was fundamental. 

The development was completed on a high-resolution desktop using browser developer tools to adjust display scale to replicate smaller devices. I also experimented with other browsers, and ran into particular issue with elements of flexbox not being incorporated with an older version of internet explorer, and thus adjusted my strategy to use floats to accommodate more browser generations. 

To improve the responsive nature of the site, I added an additional breakpoint at 980px outside of the planned mobile breakpoint of 480px. This allowed for better formatting of the header and footer when using larger mobile devices and shrinking the window while using a desktop. Rigorous trial and error using browser developer tools was key in this process to fine-tune the formatting of elements for optimal alignment and display. 

I also tested the site against the accessibility criteria for compliance. This uncovered small shortcomings to be amended, such adding alts to all site images. With improved appreciation of the accessibility specifications through further development, simple errors like these would become engrained into the development process naturally. 

An area of functionality omitted in this assignment was the posting and retrieval of data to and from a back-end LMUK server. This capability was beyond the scope of the assignment as it would require access to LMUK secure servers, alongside API development to interface to the site. This would have been effective in the saving of student workbook notes and personal information comments, as well as the uploading of a CV to the LMUK servers. 

To conclude, the site is capable of presenting the required information to the user in a high-quality standard. 