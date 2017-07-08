FUT-Consumables-Resource-IDs
This is a listing of all of the consumables in FIFA 17 including a description 
for the various columns that come back from a search of consumables in the club. 
This is what they apear to mean:

item/amount:
- for the Fitness, Healing, GK Training, and Training cards, this is the amount of the impact to the player
- for the Contracts the impact is in the item/bronze, item/silver, item/gold field
- for the Manager League cards this is the league of the card from the FUT Types JSON

item/cardassetid - this is the category of the consumable:
- AssetId / Category,
- 7 / Contract
- 8 / Contract - Manager
- 10 / Fitness
- 9 / Healing
- 3 / GKTraining
- 1 / Training
- 34 / Positioning
- 50 / Chemistry Style
- 51 / GK Chemistry Style
- 32 / Manager League
                
item/cardsubtypeid - this appears to be tied to the image on the card
                     
item/pile - this is the same for all and I assume that it means "club"

item/rare - 0 is non-rare and 1 is rare

item/rating - just like players - gold consumables are 75-95, silver 65-74, and bronze 50-64

item/resourceGameYear - self explanatory

item/weightrare - 0 for non-rares and > 0 for rares. No idea what it is used for

item/resourceId:
- this is the number that is used used to search for a specific consumable on the transfer market. 
- maskedDefId=resourceId
- this URL is an example of a "compare prices" done for All Healing Gold.      
"https://utas.external.s3.fut.ea.com/ut/game/fifa17/transfermarket?type=development&start=0&num=16&maskedDefId=5002030"

If you use a compare prices search to find specific consumables, you must use the correct transfer market:
- transfermarket?type=development - used for contracts, fitness, healing
- transfermarket?type=training -used for player training, GK training, position change, chemistry styles, manager league

Class, Category, Level, and Type are the headings that I used to keep track of the descriptions                   

I did learn how to program in machine language using octal in the 80s for a computer the size of a refrigerator, so I understand how 
programs work and boolean algebra, but I am not a coder or a programmer. If you find any mistakes please let me know.
                   
