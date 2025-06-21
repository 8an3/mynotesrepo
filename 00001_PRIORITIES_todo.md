# PRIORITIES

- [x] stock data dialog, put in create currentMy, create unit and the units files as well where you can edit inventory items not the unit file as in sales
- [ ] how do csis go to customers
- [ ] when creating currentMYModels make sure they attach to the dealer in the database
- [ ] need to update create currentMY page
- [ ] need to do quick walkthrough video from main site for dealers to look at 
- [ ] need to update admin due to schema change for DealRequest or whever deal requests are done
- [ ] unicorn search needs to be completed
- [ ] CustomTemplatePrint need to repalce with actual print
- [ ] PrintPdf same as above



- [ ] -------- CALENDAR --------
- [ ] time presets - service appointment setter
- [ ] chart filter - end of day reports, reports, leaderboasrd, sales stats
- [ ] need to create action and add forms to on drop and such for service calendar
- [ ] redo service right sidebar
- [ ] neeed to add communications abilties to mobile sales dashboard
- [ ] client setter
- [ ] /workOrder/calendar/:workOrderId for setting initial appointment to mechanic use time preset
- [x] for service calendar for service writer, use with time presets, but put the presets in the footer x the amount of mechanices, first col would be tech 1 second col would be tech 2 so they can see all of their techs appts at once and have the workorder display on the right side the full length so they can quickly roll through events




- [ ] -------- SALES --------
- [ ] show sales funnel percentages appts to quotes to sales converted
- [ ] UNITFILE FINANCE CALC - Need to somehow get all the totals from the finance tab to the deposits tab maybe use redux somehow....
- [ ] FINANCE CALC - need to ensure all options figures are going through
- [ ] FINANCE CALC - need to update options overview in sales - once options are selected we need to add the total together and save it to the finance object to be used in the finance calc
- [ ] need a way to input custom line items for bos so extra items can be inputted
- [ ] unit file - need to find a way to see if all signatures have beeen signed, maybe add new field in the schema that couunts all the signatures when the user saves beforesending to client, when client signs get number from db and count how many signatures are in inputs since inputs only shows the signatures completed
- [ ] unit file - notify user that inventory isnt assigned, same with setting it to sold
- [ ] Unit Notifier - Never miss a sales opportunity again. Our intelligent alert system automatically notifies customers when their desired vehicle arrives in inventory, creating instant sales opportunities
- [ ] create page to create, edit currentMY
- [ ] make sure finance handoff works
- [ ] dealer/accessories/newOrder/cm06lhi4u0001lb03xvaq4gwu print receipt not working in prod
- [ ] mass email - need to redo


- [ ] -------- PDF --------
- [ ] Send notifications
- [x] Label Generation: 
- [x] Dynamic label layouts 
- [x] Batch printing
- [ ] connect pdf signer with client portal
- [x] label maker


- [ ] -------- INVENTORY --------
- [ ] refunded deposit button to remove it from unit file and put it back up for sale
- [ ] setting to sold, use seearch command search to search for unit file

- [ ] -------- CLIENT SITE --------
- [ ] sales quotes tab, finish actions 
- [ ] sales finance app, require clienbt to upload dl
- [ ] in client portal sales quotes tab, finish actions 
- [ ] in client portal sales finance app, require clienbt to upload dl
- [ ] need to create `/dealer/currentMY/reserveNow/${model.id}`
- [ ] need to create `/dealer/currentMY/contact/${model.id}`
- [ ] and do something with the save feature from the byo
- [ ] service scheduler
- [ ] for client site we need to filter out current my units that are displayed by the current year, already updated sales/options so we can copy it from there
- [ ] need to update client site configurator to accomadate more complex models ie manitou


- [ ] -------- SERVICE --------
- [x] SERVICE WRITER CALENDAR - second appt through calendar scheduler or check if the same appointment can be stretched to the following day going into the next day, still need a way to add custom spots have a searchable drop down to choose client for appointment then searchable dropdown for the work order number to select the work order to attach it to, then just let them customize the rest with just a text area for them to leave a comment for a description for the appointment 
- [ ] WORKORDER CALENDAR - second appt through calendar scheduler or check if the same appointment can be stretched to the following day going into the next day, still need a way to add custom spots have a searchable drop down to choose client for appointment then searchable dropdown for the work order number to select the work order to attach it to, then just let them customize the rest with just a text area for them to leave a comment for a description for the appointment 
- [ ] WORKORDER - scheduler for empty brands have it select all technicians
- [ ] service scheduler
- [ ] delivery calendar - put in print day incase the driver doesnt have a cell/ charger

- [ ] -------- TUTORIALS AND REFERENCE --------
- [ ] need to do videos for each position

- [ ] -------- DEV --------
- [ ] move to a different site that isnt public facing, or atleast a different address then our public site, that way if someone does gain access they dont have access to your dealers data
- [ ] back ups of databases for dealers once in production?
- [ ] CHECK SUBSCRIPTION move to dev and the last day of the month run the script through automation, or set up an api to get the alerts
- [ ] DEV / CONTROLPANEL vercel api response when saving dealer details save projectName
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



- [ ] -------- COMPLETED --------
- [x] started on creating my own pdf me
- [x] admin - display punch clock values so admin can easily do payroll
- [x] need to add finance buffer somewhere in admin
- [ ] dev
- [x] in loader put const partnerSite = dealer.partnerSite to gain access to calendar site
- [x] need dashboard to connect to all the dealers dashboards
- [x] in order for dealers to have the latest data for the roadmap we need to make it an api request to the main website, which may not work due to cors...
- [ ] general
- [x] in the right side bar header put a left and right chevron on the ends to control the days of the calendar without having to open it
- [x] sales dashboard when a client doesnt have a unit on file, isntead of how it is currently because it resets the dashbaord list anyways change it to open a dialog to select a brand and then a model, the brand list get actvated brands
- [x] in sidebar filter by resource id
- [x] left off at cal sidebar, had calendar working need to finish appt dialog, client im chat, email client is working but the ui is kinda funky, was trying to fix classname of content remove all heights as the sidebar takes car of the overflow y auto itself so we shouldnt be set that and those funky fucking flex-col that seems to completely disrup any overflow y auto before it
- [x] create scripts viewer that is movable so sales people can move it around the screen or close when needed
- [x] admin user schduling  for dealers or schedules that are a bit more all over the place each userSchedule will need to have a date will have its own set day so i fixed the schema but i want to accomadte for both scheduling styles so the managers that can set a fixed schedule every week never have to come back to do this, but the managers that need to have more control in scheduling it also accomadats them too  can we change it to accomdate both styles?
- [ ] tutorials
- [x] in getting started page u explain that each section has a tutorial on the page it self... need to add those
- [x] need to add legend for docs, Service Work Order, Bill Of Sale, so as to know which when they create the docs
- [x] finance.salesStatus to show the customer where the bike is currently if its on order, at the shop, in service etc need to set this up in the unit file
- [ ] service
- [x] ned to finish off the action in book service
- [ ] sales
- [x] need to redo clientfile
- [x] make sms and email client draggable
- [x] put combo box in text editor for atributes
- [x] should go over notificationsUser.create at some point
- [x] show unread emails in side bar? and text messages?
- [x] test new mgrs calculator implementation
- [x] remove bmwmoto and manoptions from finance calc
- [x] EMAIL - for email use email sidebar from shadcn sidebars now in /components/emails/ui
- [ ] CALENDAR
- [x] disable right sidebar for mobile?
- [x] service cal, have calendar on the left with the options of filtering, then everything to the right each column will be a technician, and displays each of their appointments through out the day, do custom drag and drop
- [x] redo tech cal
- [x] sms is redone in calsidebar needs to be tested before moving to everyhwhere else, this is getting all chats, the other sms for client specfic is already done with new email and phone for dashbaords already in sales dashbaord
- [x] redo sales calendar
- [x] redo sales mobile calendar
- [x] redo mobile service cal
- [x] redo sales dashbaord
- [x] redo employeee schedulers
- [x] redo sales right side bar
- [x] redo delivery cal
- [x] for sales calendar have appoinemtns show up on the right, appts change depending on the day selected, clicking on a appt display the appt in the footer
- [x] multi month and selections - time off selector
- [x] dob / dobDrawer - client file, turn dob drawer into the response diaolog and drawer
- [x] time picker inline or regualr - csales dashbaord appointment setter
- [x] with event slots - right side bar service calendar, and sales calendar, mobile sales calendar, mobile service calendar, mobile and regular tech calendar ----!!!! try to combine with inline time picker for sales appointment setter
- [ ] PDF
- [x] Database Integration: 
- [x] Connect to your existing database 
- [x] Fetch data for PDF generation 
- [x] Store completed documents
- [x] Set up your database models for templates and documents 
- [x] Implement authentication for clients to sign documents 
- [x] Add more field types (text, images, QR codes) 
- [x] Implement drag-and-drop for the template builder 
- [x] Add PDF generation with @react-pdf/renderer or similar library
- [x] @react-pdf/renderer: Used for PDF generation
- [x] react-pdf: Used for PDF viewing
- [x] PDF Signing Libraries Best Option: pdf-lib + custom implementation Why: Most flexible approach for Remix  Implementation Strategy: Use pdf-lib to add signature fields Implement your own signing workflow Store signature events in your database
- [x] Winner for Viewing Efficiency:Ã¢ÂÂ Blob (better for pure viewing, especially large documents).
- [x] Winner for Form Inputs & Signing:Ã¢ÂÂ DOM (PDFViewer) (easier to overlay interactive elements).
- [x] pdf - create and print pdfs
- [x] pdf - view pdfs
- [x] pdf - sign pdfs
- [x] pdf - create form on pdf
- [x] pdf - edit form on pdf
- [x] pdf - create template
- [x] pdf - add pdf or image as background
- [x] pdf - map fields on x and y axis so you can map inputted data
- [x] pdf - save information in meta data, opened time, amount of signatures, amount signed etc
- [x] Signature Tracking: 
- [x] Store when a client opens a document 
- [x] Track signature completion 
- [x] Template Management: 
- [x] Save templates to database 
- [x] Load existing templates 
- [x] Preview templates with sample data
- [x] QR code integration 

