# PRIORITIES

- [x] left off on new parts/accessores dashboard and tickets dashbaord pagination just stopped working beecause i think its not linked correctly from the laoder to the paginatrorfunction
- [ ] left off at harley and bmw current my uplado in the database
- [x] need to put DealerBrandsActivate on current my page and display brands current my models

- [x] finish exercise page
- [x] package.json     "postinstall": "prisma generate",
- [x] root package.json   "install": "pnpm recursive install", "i": "pnpm recursive install",
- [ ] finish poprtal/admin/inventory/create
- [x] for finishing off accessories and product page
- [ ] finish create acc
- [ ] finish acc view page
- [ ] dynamically load brands
- [x] dyna load categories
- [x] dyna load pac hero use same hero, add site/section  to hero to we can get the ones we need where we nee them
- [x] dyna load  feature items
- [x] dyna load hottest items
- [x] dyna load managers special items
- [x] save cart items in local storage
- [ ] remove auto focus on http://localhost:3000/portal/sales/inventory/UNIT_1
- [ ] the reason why http://localhost:3000/portal/sales/inventory/UNIT_1 is having weird scrolling issues is because it does not have a parent route providing the layout for it so move inventory to inventory.data, then make inventory the parent route and set overflow-y-auto so the whole page scrolls and not some weird looking container thing
- [ ] obivouisly finish accessories
- [ ] for image uploads either
- [ ] convert to data uri to store and convert back on load
- [ ] store on bucket, point img with url
- [ ] need to create a route for sales  return redirect(`/portal/sales/search/${f.dealerId}`) to search and get the required items to redirect to  return redirect(`/portal/sales/customer/${f.clientfileId}/${f.id}`)
- [ ] delete portal/sales/stockUnit... whats it for?... nvm its the unit picker... were probably gonna have to redesign that  by now
- [ ] move all current "new units" to currentMY like harley bmwmotrorrad, convert them all if u can
- [ ] ned to finish off the action in book service
- [ ] we should be getting the user to log in to submit the form if they havent yetsame in part request, demodays,


- [ ] -------- ADMIN --------
- [ ] need to make performance graphs for managers and owner, similar to sales persons version
- [ ] added bio to user
- [ ] create section to modify varaibles for client facing site
- [ ] combine portal/admin/overview and admin/settings/geenral

- [ ] -------- DASHBOARDS --------
- [ ] ALL TABLES - for controlling the amount of rows loading at a time on a dashboard look at pagination controlled from react tables

- [ ] -------- DEV --------
- [ ] move  to a different site that isnt public facing, or atleast a different address then our public site, that way if someone does gain access they dont have access to your dealers data
- [ ] back ups of databases for dealers once in production?
- [ ] make it so in the dev menu u can choose which brands each dealer has
- [ ] in order for dealers to have the latest data for the roadmap we need to make it an api request to the main website, which may not work due to cors...

- [ ] -------- SALES --------
- [ ] mass email - need to redo
- [ ] unit file - need to find a way to see if all signatures have beeen signed, maybe add new field in the schema that couunts all the signatures when the user saves beforesending to client, when client signs get number from db and count how many signatures are in inputs since inputs only shows the signatures completed
- [ ] unit file - notify user that inventory isnt assigned, same with setting it to sold
- [ ] take note from ticket.dealerid and update financeids notes, check out notes on acc and wo since tickets version is alot nicer and cleaner
- [ ] Unit Notifier - Never miss a sales opportunity again. Our intelligent alert system automatically notifies customers when their desired vehicle arrives in inventory, creating instant sales opportunities
- [ ] test new mgrs calculator implementation
- [ ] create page to create, edit currentMY

- [ ] -------- CLIENT PORTAL --------
- [ ] sales quotes tab, finish actions 
- [ ] sales finance app, require clienbt to upload dl
- [ ] in client portal sales quotes tab, finish actions 
- [ ] in client portal sales finance app, require clienbt to upload dl

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

- [ ] -------- Side bar --------
- [ ] put in right side bar?
- [ ] tickets in sidebar?

- [ ] -------- 613 MOTORSPORTS ---------
- [x] called steph, hes interested in getting it for his shop
- [x] follow up with steph
- [x] sent him questionare on what he wants to see in it 
- [ ] questions
- [ ] how do u want to discount items


