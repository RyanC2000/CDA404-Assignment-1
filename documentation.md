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





Page titles, image alts, headings, contrast ratio, text sizing, forms are labelled as required and return error if incomplete



Pictures have text alternatives. Easily readable font, colour combinations, fonts are large, no scrolling content/flashing - no steps taken to address those. 

Page titles are clear

Images and icons have a descriptive alternative

Headings are hierarchical

All selectable elements tab in top-to-bottom, left-to-right order when using the keyboard and links can be accessed using the enter key on the keyboard. 

All text entry fields on forms are set to required with and asterisk after the label to denote this. When inputs are incomplete on submission, a red border is added to the field and an alert is displayed listing the missing fields.

Once the site was developed, all content was reviewed against the W3C Accessibility Standards using [Easy Checks - A First Review of Web Accessibility](https://www.w3.org/WAI/test-evaluate/preliminary/). 

There is no moving, flashing or multimedia content on the site, so no steps have been taken to address these areas of accessibility.

### Page Titles

All page titles state the name of the site and the page topic to ensure that they are accessible.

### Images

All images and icons have been given a descriptive alternative text to assist screen readers.

### Headings

Each page has a h1 heading at the top of the main portion of the page. Subsequent headings have been implemented in a hierarchical fashion to denote the importance of a topic.

### Contrast Ratio

Text contrasts have been checked using [WebAIM's Contrast Checker](https://webaim.org/resources/contrastchecker/) to ensure sufficient readability.

### Text Resizing

All text resizes on zoom and elements do not overlap.

### Keyboard Access and Visual Focus

All selectable elements tab in top-to-bottom, left-to-right order when using the keyboard and links can be accessed using the enter key on the keyboard. 

### Forms, Labels and Errors

All text entry fields on forms are set to required with and asterisk after the label to denote this. When inputs are incomplete on submission, a red border is added to the field and an alert is displayed listing the missing fields.

## 1.1.5 GDPR



As the website is for internal use only and will be accessed securely via the company intranet, all users will already be bound by a number of policies which encompass GDPR as well as information security, computer misuse and data privacy; all of which are all available on the intranet where this site would reside. As such, it has not been deemed necessary to reference these from within the site.

Were this deployed as a standalone site used externally, a link would be included at the bottom of the page alongside the site map to the [MAXIMUS UK Privacy Policy](https://maximusuk.co.uk/privacy-policy) for reference rather than a local version held on the site itself to ensure the most up-to-date version of the policy is always being referenced. Opt-outs would also be provided on all forms to comply with GDPR.

I have tried my hardest when creating this website to ensure that I keep to the GDPR guidelines with specific attention paid to the 8 rights provided by GDPR.
One thing of note is that as this is going to be an addon to our already existing website I have linked to our Privacy policy in the footer of every one of the pages to ensure that every user has ample opportunity to read its content.
All eight rights are clearly explained in our Privacy policy and as the form currently does not submit anywhere, I do not have to implement any systems for automatic deletion of data etc. However, when we release this website the forms will submit into our backend Salesforce system where all of our automatic data deletion is handled for us so there was very little to do GDPR wise in this website.

## 1.1.6 Distance Selling

The Work Experience Portal is strictly informative and does not provide a facility for users to make a purchase of any kind, thus The Consumer Contracts (Information, Cancellation and Additional Charges) Regulations 2013 is not relevant. 

## 1.1.7 Evaluation


Moving, Flashing, or Blinking Content
Moving, flashing, or blinking content includes carousels (example carousel), ads, videos, auto-updating stock tickers, scrolling news feeds, and more. Users need to be able to control moving content, especially some people with attention deficit disorder or visual processing disorders.

Potential accessibility problems with moving, flashing, or blinking content include:

Understanding moving information — Some people read and process information slowly. The content may disappear before people have time to read it. Some people have difficulty tracking moving objects.
Distraction from moving content — Moving content can make focusing and reading elsewhere difficult; that is, people cannot focus on some content because the movement in another area of the web page grabs their attention.
Additionally, flashing or blinking content can cause seizures in people with photosensitive epilepsy, particularly if it:

flashes more than three times in one second,
covers a large enough area of the screen, and
is bright enough.
What to check for:
Check if there is any moving, blinking, or scrolling information that starts automatically and lasts more than five seconds. If there is, check that there is a way for the user to pause, stop, or hide the movement.
Check if there is any auto-updated information (such as stock price). If there is, check that there is a way for the user to pause, stop, or hide the updated information, or for the user to control the frequency of the update.
Check that no content flashes or blinks more than three times in one second. If it does, further evaluation is needed as explained in Three Flashes or Below Threshold.

You should dedicate a section in the documentation that reflectively evaluates the work that has taken place. Answering some of the below questions could help you:

To what extent did you tackle the problem that you set out to solve?
What problems did you encounter along the way?
How did you test your website/web-application on multiple devices, and what did you find out?
What informed your design choices?