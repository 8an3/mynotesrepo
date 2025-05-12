# PRIORITIES


- [x] -------- HOME PAGE --------
- [x] add variable to env variables to check to see if this is a dealers site or not, if dealers site redirectr to client face site

- [ ] -------- SEARCHES --------
- [ ] change from manual filtering to fuse
  
- [ ] -------- TICKETS --------
- [ ] moving all client coms to tickets
- [x] web leads
- [x] incoming finance apps
- [ ] display undone tickets in right side bar for each dept
- [x] the contact us page
- [x] inquire for more information on unit
- [x] reserve bike
- [ ] for finance managers add call queue, that sales people can add clients too can use ticketing system for this
- [ ] move webleads to ticketing system have it so depending on the label it shows different menus and buttons to deal with it
- [ ] filter by user when first opened

- [ ] -------- ADMIN --------
- [ ] need to make performance graphs for managers and owner, similar to sales persons version
- [ ] added bio to user
- [ ] create section to modify varaibles for client facing site

- [ ] -------- DASHBOARDS --------
- [ ] ALL TABLES - for controlling the amount of rows loading at a time on a dashboard look at pagination controlled from react tables

- [ ] -------- DEV --------
- [ ] move  to a different site that isnt public facing, or atleast a different address then our public site, that way if someone does gain access they dont have access to your dealers data
- [ ] back ups of databases for dealers once in production?
- [ ] make it so in the dev menu u can choose which brands each dealer has

- [ ] -------- SALES --------
- [ ] mass email - need to redo
- [x] unit file - need to make trade in form i think this is done
- [ ] unit file - need to find a way to see if all signatures have beeen signed, maybe add new field in the schema that couunts all the signatures when the user saves beforesending to client, when client signs get number from db and count how many signatures are in inputs since inputs only shows the signatures completed
- [ ] unit file - notify user that inventory isnt assigned, same with setting it to sold
- [ ] make it so if the file is already assigned to someone that they cant be contacted by another sales person, or display an alert diaolog warning that its already someones elses file
- [ ] take note from ticket.dealerid and update financeids notes, check out notes on acc and wo since tickets version is alot nicer and cleaner

- [ ] -------- CLIENT PORTAL --------
- [ ] sales quotes tab, finish actions 
- [ ] sales finance app, require clienbt to upload dl
- [ ] in client portal sales quotes tab, finish actions 
- [ ] in client portal sales finance app, require clienbt to upload dl

- [ ] -------- SERVICE --------
- [ ] SERVICE WRITER CALENDAR - second appt through calendar scheduler or check if the same appointment can be stretched to the following day going into the next day, still need a way to add custom spots have a searchable drop down to choose client for appointment then searchable dropdown for the work order number to select the work order to attach it to, then just let them customize the rest with just a text area for them to leave a comment for a description for the appointment 
- [ ] WORKORDER CALENDAR - second appt through calendar scheduler or check if the same appointment can be stretched to the following day going into the next day, still need a way to add custom spots have a searchable drop down to choose client for appointment then searchable dropdown for the work order number to select the work order to attach it to, then just let them customize the rest with just a text area for them to leave a comment for a description for the appointment 
- [ ] WORKORDER - scheduler for empty brands have it select all technicians

- [x] -------- AUTH --------
- [x] custom oauth in compoents/microsoft/custom.login.tsx

- [ ] -------- TUTORIALS AND REFERENCE --------
- [ ] in getting started page u explain that each section has a tutorial on the page it self... need to add those
- [ ] need to add legend for docs, Service Work Order, Bill Of Sale, so as to know which when they create the docs
- [ ] finance.salesStatus to show the customer where the bike is currently if its on order, at the shop, in service etc need to set this up in the unit file

- [ ] -------- CLIENT FACING WEBSITE --------
- [x] custom banner
- [x] custom color scheme
- [x] custom carasel
- [x] post customer reviews
- [x] custom sectoins - cleint can put as many as they want they just get taecced at the bottom of the front page
- [x] Would need to design system for inventory for front end and give the ability for customer leave a deposit with e-transfer or leave their card info for sales staff to process when they can, in sales section add the ability for editing the listing and add pictures, listings would be pre populated by current inventory so you don't have to add anymore listings, this would also be good to work with auto trader and other platforms would have to create this later because I don't know if I should populate a http response with CSV data or an API route to send the needed data to the platform to create and update listings 
- [x] unit listings, make it extremely easy for client to book appoinments, request call back, secure unit with deposit, give needed info upfront with the option to view all info
- [x] add button to listings only visibile to sales, so when they go over inventory with sales staff they can just click create unit file, then displays a command dialog to select a client or create a new one
- [x] button for client to leave deposit 
- [ ] front end as well except parts and accessories where it links to their own current providor so the landing page, and such copy Ottawa Harley Davidson pages and layout to have the same format, have sister area in admin section where dealer can fill in information that doesn't get auto filled plus a place where they can upload main photos to display their brand, althought put features like unit ediitng in portal staff so all users can edit inventory along with other items like that
- [ ] when the rest of the site is compelte work on parts and accesssories
- [x] add login for dealers users for crm
- [x] move client portal to client facing site that way it prefills in form for them and its less confusing to use and seems like one big system
- [ ] finish off nav users items
- [x] finish off assign to client buttons
- [ ] go through new lead process and all other customer contact processes



- [ ] -------- INVENTORY --------
- [ ] add button to listings, so when they go over inventory with sales staff they can just click create unit file, then displays a command dialog to select a client or create a new one
- [ ] added more models to inventory schema need to update that
- [ ] refunded deposit button to remove it from unit file and put it back up for sale
- [ ] setting to sold, use seearch command search to search for unit file
- [ ] once assigned, display button to navaigate there

- [ ] -------- STAFF CHAT --------
- [ ] put in right side bar?

- [ ] -------- 613 MOTORSPORTS --------
- [x] called steph, hes interested in getting it for his shop
- [ ] follow up with steph
- [ ] -------- CLIENT FACING SITE --------
- [ ] home page
- [ ] -------- CLIENT PORTAL? --------
- [ ] order status
- [ ] saved carts
- [ ] passwordless auth
- [ ] online chat
- [ ] indiviual acc pages
- [ ] cart
- [ ] -------- INTERNAL --------
- [ ] dashboard
- [ ] create order
- [ ] ticketing system
- [ ] -------- ACC PAGES --------
- [ ] print tags
- [ ] inventory counter
- [ ] receiving dashboard
- [ ] -------- MGR DASHBOARD --------
- [ ] performance dashbaord 
- [ ] set inventory mins for auto ordering / create auto orders for review
- [ ] -------- SETTINGS --------
- [ ] users
