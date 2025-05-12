# PRIORITIES

- [ ] -------- SEARCHES --------
- [ ] change from manual filtering to fuse
  
- [ ] -------- TICKETS --------
- [ ] for finance managers add call queue, that sales people can add clients too can use ticketing system for this
- [ ] move webleads to ticketing system have it so depending on the label it shows different menus and buttons to deal with it
- [ ] rTChatMessages.create need to search app and switch for tickets instead


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
- [ ] in order for dealers to have the latest data for the roadmap we need to make it an api request to the main website, which may not work due to cors...

- [ ] -------- SALES --------
- [ ] mass email - need to redo
- [x] unit file - need to make trade in form i think this is done
- [ ] unit file - need to find a way to see if all signatures have beeen signed, maybe add new field in the schema that couunts all the signatures when the user saves beforesending to client, when client signs get number from db and count how many signatures are in inputs since inputs only shows the signatures completed
- [ ] unit file - notify user that inventory isnt assigned, same with setting it to sold
- [ ] make it so if the file is already assigned to someone that they cant be contacted by another sales person, or display an alert diaolog warning that its already someones elses file
- [ ] take note from ticket.dealerid and update financeids notes, check out notes on acc and wo since tickets version is alot nicer and cleaner
- [x] when clients go to book their own appotinement with sales use the reserveNow.dealerid has the client login and return process done already to copy off of so that clients are seraching for an email and could potentially get other peoples emails from that

- [ ] -------- CLIENT PORTAL --------
- [ ] sales quotes tab, finish actions 
- [ ] sales finance app, require clienbt to upload dl
- [ ] in client portal sales quotes tab, finish actions 
- [ ] in client portal sales finance app, require clienbt to upload dl
- [ ] finish - parts request, copy over from client site or maybe put a button that says already a client?? login and divert to client portal version as it will populate all client fields

- [ ] -------- SERVICE --------
- [ ] SERVICE WRITER CALENDAR - second appt through calendar scheduler or check if the same appointment can be stretched to the following day going into the next day, still need a way to add custom spots have a searchable drop down to choose client for appointment then searchable dropdown for the work order number to select the work order to attach it to, then just let them customize the rest with just a text area for them to leave a comment for a description for the appointment 
- [ ] WORKORDER CALENDAR - second appt through calendar scheduler or check if the same appointment can be stretched to the following day going into the next day, still need a way to add custom spots have a searchable drop down to choose client for appointment then searchable dropdown for the work order number to select the work order to attach it to, then just let them customize the rest with just a text area for them to leave a comment for a description for the appointment 
- [ ] WORKORDER - scheduler for empty brands have it select all technicians

- [ ] -------- TUTORIALS AND REFERENCE --------
- [ ] in getting started page u explain that each section has a tutorial on the page it self... need to add those
- [ ] need to add legend for docs, Service Work Order, Bill Of Sale, so as to know which when they create the docs
- [ ] finance.salesStatus to show the customer where the bike is currently if its on order, at the shop, in service etc need to set this up in the unit file

- [ ] -------- CLIENT FACING WEBSITE --------
- [x] when the rest of the site is compelte work on parts and accesssories
- [x] finish off nav users items
- [x] reserveNow.dealerid has the client login and return process done already to copy off of
- [x] go through new lead process and all other customer contact processes
- [ ] finish off Web Lead process
- [ ] finish off accessorise
- [ ] create pages for button on inventory page, to create unit files
- [ ] page removed - virtual tour moved to components/clientsite
- [ ] page removed -  { title: "Build Your Own", url: URLS.BYO },
- [ ] page removed - promotions serfvices sales and pac, now once page
- [ ] page removed - photo gallery
- [ ] page removed -  blog
- [ ] page removed - newsletter

  
- [ ] -------- INVENTORY --------
- [ ] add button to listings, so when they go over inventory with sales staff they can just click create unit file, then displays a command dialog to select a client or create a new one
- [ ] added more models to inventory schema need to update that
- [ ] refunded deposit button to remove it from unit file and put it back up for sale
- [ ] setting to sold, use seearch command search to search for unit file
- [ ] once assigned, display button to navaigate there

- [ ] -------- STAFF CHAT --------
- [ ] put in right side bar?

- [ ] -------- 613 MOTORSPORTS ---------
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

