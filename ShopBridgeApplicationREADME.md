# ShopBridge-Application of shop bridge

  Shop Bridge Application is a application used to handle the inventory system.
 It has a functionality for Creating a new inventory, Editing the Created inventory and deleting the created inventory.
 
 In Model of this inventory there is a additional field of Del_Flag created for future purpose.
 Del_Flag was been created so the instead of hard delete on deletion of records, we can just do soft delete so that we have trace to find the inventorys which ShopBridge had earlier 
 but currently is does not exist.
 
 This crude operation is been achived through ShopBrige API.Below is the link for the same:
 https://github.com/goldayovan/ShopBrige_API
 
 
 Technology used:
 Asp.Net MVC
 SQL Server 2012
 
 
 Flow of application:
 1) Inventory Summary screen would be displayed with a grid having all the saved records with edit, delete and Add New Inventory Hyperlink
 2) On Click of Add New Inventory we get redirected to New Create Screen would be opend to add inventory.
      a) Basis validation on this screen has been added like required field, field length, duplicate check through API 
 3) On Edit from Summary grid we get redirected to Edit screen showing data which we have saved we can edit the same and save it.
 4) On Delete confirmation alert come's to confirm before delete.
