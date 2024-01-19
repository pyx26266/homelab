## Photo management
- Duplicate photos are okay. With current resources and time, make peace with it.
  - tried Digikam AI similarity finder to remove photos, then left for few months and felt like I deleted something important. Human mind is the weakest and strongest link.
  - brought back old photos then deleted again took almost 2-4 years on and off.
 
- Go with hash based deletion that is mathematically safe for human mind.
- follow 3:2:1 rule of backup for sure, to make it easy
  - SSD <-rsync-> NAS(JBOD/ZFS-mirror) + cloud (google or iCloud)
 
- AI in future gonna be powerful enough to make sense out of 0.5 millon photos (my lifetime collection size). I tried LLAVA 13b parameters and it was amazing on M1 MAcBook Air for my collection.
- with homelab we have lot of time for inference and does not cost us business loss.
- Offline AI is the ultimate goal for photo management.
- As of now, have a taste of these:
  - SSD <--> NAS + iCloud/GogleOne
  - A photo wall with best of the best group photos is must.
  - Phone wallpaper with you landscape photos.
  - Photoprism/Immich to manage half a million photos with small AI search and segmentation.
 

## Finance management 
- Sounds important for every household unless you don't want to give an edge to YOUR plaintiff 😉.
- Started with some random Android app and settled to GNUCash mobile app.
- Fell in love with double entry bookkeeping, why it's not taught to engineers.
- next Financial year moved to GNUCash PC app, I'm into iOS ecosystem, I was so impressed by GNUCash that I had to get a costly Computer (MAC) just for this; just kidding, I needed a homelab server.
- after 2 more FY, I realised the love is not enough I need more control over reports, Finance was getting complicated with splits and investments and was not visible in reports.
- Come to Excel, Oh wait! I don't have one, come to Numbers in Apple universe. Good enough, it can do anything, can generate fun reports BUT is all manual.
- 2 eternity (FY) later, found another love on reddit r/selfhosted. We can have finance manager web app hosted on Server as well, blew my mind.
- It has all the features I was longing for years,
  - portable to mobile/PC
  - sankey diagram
  - double entry bookkeeping
  - beautiful report diagrams as excel.
  - and can be seamlessly integrated with holab environment for IAM.
 
- I know it's most precious data to be stored so close to disaster, many will like it locally on phone or Oflfine PC app. But hey, that's where we miss Automation!
- Found, Actual/Firefly-iii/Paisa. After trying all these, found Paisa.fyi to be more intuitive, database is open text format and can be moved to another app easily compared to other where we need to depend on their export form SQL Db.
- Tried setting up isolated environment with pfSense+Docker having block all outbound traffic except one or two domain. Failed miserably.
- Due to limited resource need to trust developer and its dependencies to not siphone out data.
- Even after isolating server, data can be sent thorough client browser. RIGHT?
- Tried auditing the github repo for malicious code and dependencies, haven't found any. Will keep close eye on future commits.
 
