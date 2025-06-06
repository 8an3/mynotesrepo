# PRIORITIES

- [ ] stock data dialog
- [ ] how do csis go to customers
- [ ] admin - display punch clock values so admin can easily do payroll
- [ ] when creating currentMYModels make sure they attach to the dealer in the database
- [ ] need to update create currentMY page
- [ ] need to add finance buffer somewhere in admin
- [ ] need to do quick walkthrough video from main site for dealers to look at 


- [ ] -------- SALES --------
- [x] EMAIL - for email use email sidebar from shadcn sidebars now in /components/emails/ui
- [ ] show sales funnel percentages appts to quotes to sales converted
- [ ] UNITFILE - Need to somehow get all the totals from the finance tab to the deposits tab maybe use redux somehow....
- [x] remove bmwmoto and manoptions from finance calc
- [ ] need to update options overview in sales - once options are selected we need to add the total together and save it to the finance object to be used in the finance calc
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
- [ ] in order for dealers to have the latest data for the roadmap we need to make it an api request to the main website, which may not work due to cors...
- [ ] CHECK SUBSCRIPTION move to dev and the last day of the month run the script through automation, or set up an api to get the alerts
- [x] in loader put const partnerSite = dealer.partnerSite to gain access to calendar site
- [ ] DEV / CONTROLPANEL when saving dealer details save projectName
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


