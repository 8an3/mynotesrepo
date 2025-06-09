# PRIORITIES

- [ ] left off at cal sidebar, had calendar working need to finish appt dialog, client im chat, email client is working but the ui is kinda funky, was trying to fix classname of content remove all heights as the sidebar takes car of the overflow y auto itself so we shouldnt be set that and those funky fucking flex-col that seems to completely disrup any overflow y auto before it
- [ ] stock data dialog, put in create currentMy, create unit and the units files as well where you can edit inventory items not the unit file as in sales
- [ ] how do csis go to customers
- [ ] admin - display punch clock values so admin can easily do payroll
- [ ] when creating currentMYModels make sure they attach to the dealer in the database
- [ ] need to update create currentMY page
- [ ] need to add finance buffer somewhere in admin
- [ ] need to do quick walkthrough video from main site for dealers to look at 
- [ ] admin need to update DealRequest due to schema change
- [x] admin user schduling  for dealers or schedules that are a bit more all over the place each userSchedule will need to have a date will have its own set day so i fixed the schema but i want to accomadte for both scheduling styles so the managers that can set a fixed schedule every week never have to come back to do this, but the managers that need to have more control in scheduling it also accomadats them too  can we change it to accomdate both styles?
- [ ] create scripts viewer that is movable so sales people can move it around the screen or close when needed
- [ ] unicorn search needs to be completed
- [ ] started on creating my own pdf me

- [ ] -------- CALENDAR --------
- [ ] with event slots - right side bar service calendar, and sales calendar, mobile sales calendar, mobile service calendar, mobile and regular tech calendar ----!!!! try to combine with inline time picker for sales appointment setter
- [ ] time presets - service appointment setter
- [ ] multi month and selections - time off selector
- [ ] dob / dobDrawer - client file, turn dob drawer into the response diaolog and drawer
- [x] time picker inline or regualr - csales dashbaord appointment setter
- [ ] chart filter - end of day reports, reports, leaderboasrd, sales stats
- [x] for service calendar for service writer, use with time presets, but put the presets in the footer x the amount of mechanices, first col would be tech 1 second col would be tech 2 so they can see all of their techs appts at once and have the workorder display on the right side the full length so they can quickly roll through events
- [x] for sales calendar have appoinemtns show up on the right, appts change depending on the day selected, clicking on a appt display the appt in the footer
- [ ] redo tech cal
- [x] redo delivery cal
- [x] service cal
- [x] redo sales calendar
- [ ] redo sales mobile calendar
- [x] redo mobile service cal
- [x] redo sales dashbaord
- [x] redo employeee schedulers
- [x] redo sales right side bar
- [ ] redo service right sidebar


- [ ] -------- SALES --------
- [x] EMAIL - for email use email sidebar from shadcn sidebars now in /components/emails/ui
- [ ] show sales funnel percentages appts to quotes to sales converted
- [ ] UNITFILE FINANCE CALC - Need to somehow get all the totals from the finance tab to the deposits tab maybe use redux somehow....
- [x] remove bmwmoto and manoptions from finance calc
- [ ] FINANCE CALC - need to ensure all options figures are going through
- [ ] FINANCE CALC - need to update options overview in sales - once options are selected we need to add the total together and save it to the finance object to be used in the finance calc
- [ ] need a way to input custom line items for bos so extra items can be inputted
- [ ] unit file - need to find a way to see if all signatures have beeen signed, maybe add new field in the schema that couunts all the signatures when the user saves beforesending to client, when client signs get number from db and count how many signatures are in inputs since inputs only shows the signatures completed
- [ ] unit file - notify user that inventory isnt assigned, same with setting it to sold
- [ ] Unit Notifier - Never miss a sales opportunity again. Our intelligent alert system automatically notifies customers when their desired vehicle arrives in inventory, creating instant sales opportunities
- [x] test new mgrs calculator implementation
- [ ] create page to create, edit currentMY
- [ ] make sure finance handoff works
- [ ] dealer/accessories/newOrder/cm06lhi4u0001lb03xvaq4gwu print receipt not working in prod
- [ ] mass email - need to redo
- [x] need to redo clientfile
- [ ] make sms and email client draggable
- [x] put combo box in text editor for atributes
- [x] should go over notificationsUser.create at some point
- [ ] show unread emails in side bar? and text messages?



- [ ] -------- PDF --------
- [ ] pdf - create and print pdfs
- [ ] pdf - view pdfs
- [ ] pdf - sign pdfs
- [ ] pdf - create form on pdf
- [ ] pdf - edit form on pdf
- [ ] pdf - create template
- [ ] pdf - add pdf or image as background
- [ ] pdf - map fields on x and y axis so you can map inputted data
- [ ] pdf - save information in meta data, opened time, amount of signatures, amount signed etc
- [ ] Signature Tracking: 
- [ ] Store when a client opens a document 
- [ ] Track signature completion 
- [ ] Send notifications
- [ ] Template Management: 
- [ ] Save templates to database 
- [ ] Load existing templates 
- [ ] Preview templates with sample data
- [ ] Label Generation: 
- [ ] QR code integration 
- [ ] Dynamic label layouts 
- [ ] Batch printing
- [ ] Database Integration: 
- [ ] Connect to your existing database 
- [ ] Fetch data for PDF generation 
- [ ] Store completed documents
- [ ] Set up your database models for templates and documents 
- [ ] Implement authentication for clients to sign documents 
- [ ] Add more field types (text, images, QR codes) 
- [ ] Implement drag-and-drop for the template builder 
- [ ] Add PDF generation with @react-pdf/renderer or similar library
- [ ] @react-pdf/renderer: Used for PDF generation
- [ ] react-pdf: Used for PDF viewing
- [ ] PDF Signing Libraries Best Option: pdf-lib + custom implementation Why: Most flexible approach for Remix  Implementation Strategy: Use pdf-lib to add signature fields Implement your own signing workflow Store signature events in your database
- [ ] Winner for Viewing Efficiency:✅ Blob (better for pure viewing, especially large documents).
- [ ] Winner for Form Inputs & Signing:✅ DOM (PDFViewer) (easier to overlay interactive elements).


- [ ] -------- INVENTORY --------
- [ ] refunded deposit button to remove it from unit file and put it back up for sale
- [ ] setting to sold, use seearch command search to search for unit file

- [ ] -------- CLIENT SITE --------
- [ ] sales quotes tab, finish actions 
- [ ] sales finance app, require clienbt to upload dl
- [ ] in client portal sales quotes tab, finish actions 
- [ ] in client portal sales finance app, require clienbt to upload dl
- [x] ned to finish off the action in book service
- [ ] need to create `/dealer/currentMY/reserveNow/${model.id}`
- [ ] need to create `/dealer/currentMY/contact/${model.id}`
- [ ] and do something with the save feature from the byo
- [ ] service scheduler
- [ ] for client site we need to filter out current my units that are displayed by the current year, already updated sales/options so we can copy it from there
- [ ] need to update client site configurator to accomadate more complex models ie manitou


- [ ] -------- SERVICE --------
- [ ] SERVICE WRITER CALENDAR - second appt through calendar scheduler or check if the same appointment can be stretched to the following day going into the next day, still need a way to add custom spots have a searchable drop down to choose client for appointment then searchable dropdown for the work order number to select the work order to attach it to, then just let them customize the rest with just a text area for them to leave a comment for a description for the appointment 
- [ ] WORKORDER CALENDAR - second appt through calendar scheduler or check if the same appointment can be stretched to the following day going into the next day, still need a way to add custom spots have a searchable drop down to choose client for appointment then searchable dropdown for the work order number to select the work order to attach it to, then just let them customize the rest with just a text area for them to leave a comment for a description for the appointment 
- [ ] WORKORDER - scheduler for empty brands have it select all technicians
- [ ] service scheduler
- [ ] delivery calendar - put in print day incase the driver doesnt have a cell/ charger


- [ ] -------- TUTORIALS AND REFERENCE --------
- [x] in getting started page u explain that each section has a tutorial on the page it self... need to add those
- [x] need to add legend for docs, Service Work Order, Bill Of Sale, so as to know which when they create the docs
- [x] finance.salesStatus to show the customer where the bike is currently if its on order, at the shop, in service etc need to set this up in the unit file
- [ ] need to do videos for each position


- [ ] -------- DEV --------
- [ ] move to a different site that isnt public facing, or atleast a different address then our public site, that way if someone does gain access they dont have access to your dealers data
- [ ] back ups of databases for dealers once in production?
- [x] in order for dealers to have the latest data for the roadmap we need to make it an api request to the main website, which may not work due to cors...
- [ ] CHECK SUBSCRIPTION move to dev and the last day of the month run the script through automation, or set up an api to get the alerts
- [x] in loader put const partnerSite = dealer.partnerSite to gain access to calendar site
- [ ] DEV / CONTROLPANEL vercel api response when saving dealer details save projectName
- [x] need dashboard to connect to all the dealers dashboards
- [ ] DASHBOARD - to manage phone numbers for users
- [ ] DASHBOARD - to monitor / and charge correct amounts for text / voice / email
- [ ] DASHBOARD - manager potential customer base
- [ ] DASHBOARD - manage authentication for emergencies for dealers
- [ ] add cors to /portal/dev/api/roadmap


- [ ] -------- 613 MOTORSPORTS ---------
- [x] called steph, hes interested in getting it for his shop
- [x] follow up with steph
- [x] sent him questionare on what he wants to see in it 
- [ ] questions
- [ ] how do u want to discount items


