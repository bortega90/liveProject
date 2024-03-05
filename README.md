# liveProject
I had the opportunity to do a mock Azure Dev Ops project for two weeks. I posted screen recordings of the finished pages and posted some screenshots of my code.

<h3>Scaffold create/edit/delete Pages</h3>
Scaffold Razor Pages in ASP.NET Core 

<h3>Label Change</h3>
On the Create and Edit page, when "Damages" checkbox is checked, the lable changes from "Notes" to "Damages Incurred".

<h3>Collapse Accordion Menu</h3>
I used bootstrap to create a accordion menu that collapse open and close

<h3>Sorting</h3>
I used JavaScript to sort through inventory based on items that are damaged or not, a-z/z-a, and back to original state where newest entries are top of table.

<h3>Authorized Pages</h3>
In order to ensure secure and seamless management of inventory, I've implemented a robust authentication system. Users are required to sign in with credentials before making any changes to the inventory, whether it's creating a new item, editing an existing one, or deleting an item. Those who are not signed in are gracefully directed to a view page indicating unauthorized access. This was achieved by integrating a custom model inheriting the AuthorizedAttribute within the ASP.NET Framework. Subsequently, I've strategically placed the [HistoryManagerAuthorized] model atop the create, edit, and delete methods within the controller, ensuring adherence to stringent security protocols while maintaining a user-friendly experience

<h3>Seed()</h3>
I employed the seed method to strategically add an authorized user entry into the database, granting them exclusive permission to execute alterations to the data. Within this method, I meticulously defined parameters such as User Name, Email, and Password, thereby establishing a secure and authenticated access point for pivotal data manipulation.


