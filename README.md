# liveProject
During a transformative two-week engagement, I immersed myself in an Azure DevOps project, leveraging state-of-the-art methodologies to orchestrate seamless software development and deployment pipelines. Demonstrating a commitment to transparency and excellence, I curated a comprehensive portfolio of screen recordings showcasing the polished end-products, complemented by strategically selected code snapshots. Through this multifaceted approach, I not only showcased the tangible outcomes of the project but also underscored my dedication to delivering high-quality solutions while adhering to industry best practices

<h3>Scaffold create/edit/delete Pages</h3>
Utilizing the cutting-edge capabilities of ASP.NET Core, I employed Scaffold Razor Pages to streamline the development process. This sophisticated approach seamlessly generates a framework for dynamic web applications, leveraging the power of Razor syntax to rapidly scaffold out robust and highly responsive user interfaces. By harnessing this innovative toolset, I optimized efficiency and accelerated the creation of scalable and feature-rich web solutions.

<h3>Label Change</h3>
Employing advanced user interface design principles, I orchestrated a dynamic feature within the Create and Edit page. Through intelligent programming, when the 'Damages' checkbox is activated, the label undergoes a sophisticated transformation from 'Notes' to 'Damages Incurred', providing users with real-time contextual feedback that enhances usability and clarity within the interface.

<h3>Collapse Accordion Menu</h3>
I adeptly harnessed the power of Bootstrap to engineer an accordion menu, distinguished by its seamless functionality that elegantly collapses and expands with fluidity. Leveraging Bootstrap's robust framework, I orchestrated a user-centric design that seamlessly harmonizes intuitive navigation with a visually captivating interface, enhancing the overall user experience.
<h3>Sorting</h3>
I used JavaScript to sort through inventory based on items that are damaged or not, a-z/z-a, and back to original state where newest entries are top of table.

<h3>Authorized Pages</h3>
In order to ensure secure and seamless management of inventory, I've implemented a robust authentication system. Users are required to sign in with credentials before making any changes to the inventory, whether it's creating a new item, editing an existing one, or deleting an item. Those who are not signed in are gracefully directed to a view page indicating unauthorized access. This was achieved by integrating a custom model inheriting the AuthorizedAttribute within the ASP.NET Framework. Subsequently, I've strategically placed the [HistoryManagerAuthorized] model atop the create, edit, and delete methods within the controller, ensuring adherence to stringent security protocols while maintaining a user-friendly experience

<h3>Seed()</h3>
I employed the seed method to strategically add an authorized user entry into the database, granting them exclusive permission to execute alterations to the data. Within this method, I meticulously defined parameters such as User Name, Email, and Password, thereby establishing a secure and authenticated access point for pivotal data manipulation.


