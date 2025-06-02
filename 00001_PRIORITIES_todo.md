# PRIORITIES

- [x] IMAGES - for image uploads either
- [ ] IMAGES - convert to data uri to store and convert back on load like in /portal/admin/dashboard
- [x] IMAGES - store as blob, started in /portal/api/image/create
- [ ] EMAIL - for email use email sidebar from shadcn sidebars now in /components/emails/ui
- [x] dealers dialog
- [ ] clients dialog
- [x] client site dialog
- [ ] data scraper
- [x] ie dialog
- [x] reports dialog 
- [ ] users dialog

- [ ] -------- ACCESSORIES --------
- [x] need to auto inventory order to inventory page so you know what to order due to min levels compared to in stock

- [ ] -------- ADMIN --------
- [x] added bio to user
- [x] redo /admin/users/user.$userId
- [ ] finish /admin/users/user.create
- [ ] finish /admin/inventory/unit/create need to make sure it pulls stock data when creating



- [ ] -------- SALES --------
- [ ] mass email - need to redo
- [ ] unit file - need to find a way to see if all signatures have beeen signed, maybe add new field in the schema that couunts all the signatures when the user saves beforesending to client, when client signs get number from db and count how many signatures are in inputs since inputs only shows the signatures completed
- [ ] unit file - notify user that inventory isnt assigned, same with setting it to sold
- [ ] take note from ticket.dealerid and update financeids notes, check out notes on acc and wo since tickets version is alot nicer and cleaner
- [ ] Unit Notifier - Never miss a sales opportunity again. Our intelligent alert system automatically notifies customers when their desired vehicle arrives in inventory, creating instant sales opportunities
- [ ] test new mgrs calculator implementation
- [ ] create page to create, edit currentMY
- [ ] make sure finance handoff works
- [ ] dealer/accessories/newOrder/cm06lhi4u0001lb03xvaq4gwu print receipt not working in prod


- [ ] -------- CLIENT SITE --------
- [ ] sales quotes tab, finish actions 
- [ ] sales finance app, require clienbt to upload dl
- [ ] in client portal sales quotes tab, finish actions 
- [ ] in client portal sales finance app, require clienbt to upload dl
- [ ] ned to finish off the action in book service
- [ ] need to create `/dealer/currentMY/reserveNow/${model.id}`
- [ ] need to create `/dealer/currentMY/contact/${model.id}`
- [ ] and do something with the save feature from the byo

- [ ] -------- SERVICE --------
- [ ] SERVICE WRITER CALENDAR - second appt through calendar scheduler or check if the same appointment can be stretched to the following day going into the next day, still need a way to add custom spots have a searchable drop down to choose client for appointment then searchable dropdown for the work order number to select the work order to attach it to, then just let them customize the rest with just a text area for them to leave a comment for a description for the appointment 
- [ ] WORKORDER CALENDAR - second appt through calendar scheduler or check if the same appointment can be stretched to the following day going into the next day, still need a way to add custom spots have a searchable drop down to choose client for appointment then searchable dropdown for the work order number to select the work order to attach it to, then just let them customize the rest with just a text area for them to leave a comment for a description for the appointment 
- [ ] WORKORDER - scheduler for empty brands have it select all technicians

- [ ] -------- TUTORIALS AND REFERENCE --------
- [ ] in getting started page u explain that each section has a tutorial on the page it self... need to add those
- [ ] need to add legend for docs, Service Work Order, Bill Of Sale, so as to know which when they create the docs
- [ ] finance.salesStatus to show the customer where the bike is currently if its on order, at the shop, in service etc need to set this up in the unit file

- [ ] -------- CLIENT FACING WEBSITE --------
- [ ] service scheduler
  
- [ ] -------- INVENTORY --------
- [ ] refunded deposit button to remove it from unit file and put it back up for sale
- [ ] setting to sold, use seearch command search to search for unit file


- [ ] -------- DEV --------
- [ ] move to a different site that isnt public facing, or atleast a different address then our public site, that way if someone does gain access they dont have access to your dealers data
- [ ] back ups of databases for dealers once in production?
- [ ] in order for dealers to have the latest data for the roadmap we need to make it an api request to the main website, which may not work due to cors...
- [ ] CHECK SUBSCRIPTION move to dev and the last day of the month run the script through automation, or set up an api to get the alerts
- [ ] in loader put const partnerSite = dealer.partnerSite to gain access to calendar site
- [ ] DEV / CONTROLPANEL when saving dealer details save projectName
- [ ] need dashboard to connect to all the dealers dashboards
- [ ] DASHBOARD - to manage phone numbers for users
- [ ] DASHBOARD - to monitor / and charge correct amounts for text / voice / email
- [ ] DASHBOARD - manager potential customer base
- [ ] DASHBOARD - manage authentication for emergencies for dealers


- [ ] -------- 613 MOTORSPORTS ---------
- [x] called steph, hes interested in getting it for his shop
- [x] follow up with steph
- [x] sent him questionare on what he wants to see in it 
- [ ] questions
- [ ] how do u want to discount items

- [x] create section to modify varaibles for client facing site
- [x] move roles to dev so you can control the dealers roles from there
- [x] need to subscription portal
- [x] ALL TABLES - for controlling the amount of rows loading at a time on a dashboard look at pagination controlled from react tables, we are pull data a lot more effeciently than activix so it doesnt slow down as much as theirs, tested at 1000
- [x] combine portal/admin/overview and admin/settings/geenral
- [x] finish poprtal/admin/inventory/unit/create,  stock data is already created from current model years, just need to add model names ( i think ) to each of the database entries
- [x] make it so in the dev menu u can choose which brands each dealer has
- [x] to login as any dealer user, have seperate dealer site where its closed off to everyone but dev and have the authentication login as user with their dealers db
- [x] log into any dealers site - completed ensure dev user so you can log into any website
- [x] the reason why http://localhost:3000/portal/sales/inventory/UNIT_1 is having weird scrolling issues is because it does not have a parent route providing the layout for it so move inventory to inventory.data, then make inventory the parent route and set overflow-y-auto so the whole page scrolls and not some weird looking container thing
