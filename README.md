# BlazoreDX
## Modular, Scalable, and Multi-Tenant Web Application Platform

**BlazoreDX** is a Blazor Server-based, modular, extensible, and multi-tenant supported web application platform. While offering a rich user experience with DevExpress components, it provides a strong infrastructure for enterprise applications with features such as dynamic authorization and multi-language support.

---

### 1. Core Architecture
- **Blazor Server**: Real-time data management and user interaction.
- **Modular Structure**: Each module can be developed and integrated independently.
- **Dependency Injection (DI)**: All services are managed according to DI principles.
- **Event-Driven Approach**: A reactive system that tracks application events.
- **Asynchronous Programming**: Supports heavy asynchronous data processing to improve performance.
- **Platform Independence**: Developed on the Microsoft .NET 9+ platform.

---

### 2. Authorization and Authentication
- **ASP.NET Identity Integration**: User, role, and claim-based authorization.
- **Claim-Based Authorization**: Permissions can be defined specifically for users and roles.
- **Dynamic Permission Updates**: Permissions can be updated during the user session.
- **Service-Based Identity Management**: Direct service usage for user and role operations (without API dependencies).

---

### 3. Multi-Language Support (Localization)
- **User-Based Language Selection**: Users can choose their preferred language.
- **JSON or Database-Backed Translation Management**: Translations can be managed centrally.
- **Automatic Language Detection**: The default language can be set based on the user's browser language.
- **Dynamic Content Updates**: Translation changes can be reflected instantly.

---

### 4. Tenant (Multi-Tenant) Support
- **Multi-Tenant Architecture**: Allows serving multiple clients from a single application.
- **Tenant-Based Authorization**: Separate user, role, and permission management for each tenant.
- **Data Isolation**: Ensures data security and privacy between tenants.
- **Sub-Tenant Structure**: Multi-level authorization support for large organizational structures.

---

### 5. Data Management
- **SQL Server Usage**: Robust and scalable database management.
- **GUID-Based ID Usage**: GUIDs are used for all identity fields to ensure data security and integrity.
- **Entity Framework Core Support**: Strong data management with ORM support.
- **Audit Logging**: Detailed tracking of user operations.

---

### 6. User Experience and Management
- **Dynamic Menu Management**: Menus are automatically defined based on user permissions.
- **Component-Based Structure**: Customizable UI components for developers.
- **Real-Time Notifications**: Instant updates and notifications for users.
- **Custom Themes and Theme Management**: Users can switch between different themes.

---

### 7. Extensibility and Integration
- **Microservices Support**: Independent service integration thanks to the modular architecture.
- **Web API Integration**: API support for integrating with external systems.
- **3rd Party Service Integration**: Data fetching and synchronization from external services.
- **Docker and Kubernetes Support**: Application can be managed in containers.
- **OpenIconic Integration**: BlazoreDX integrates the OpenIconic library for icons, enriching the user interface with modern and customizable icons. This makes the use of visual elements more efficient.

---

### 8. Automatic Validation
Form data can be automatically validated during user input. This feature allows error messages to be displayed instantly, so users are quickly informed if they enter incorrect information. You can also customize the error messages in different languages using the language support for users in various regions.

---
### Contact 
**E-mail:** idris.sanda@oresoft.net

#### Since the DevExpress licensing procedures have been reviewed, I have not yet shared the codes.
#### You can contact me via email for the codes.

---

### Screnshoots:
Sample screenshots have been added. Below are some example images showcasing the BlazoreDX interface:

**1.Login**
![Login](https://raw.githubusercontent.com/idrissanda/BlazoreDx/refs/heads/main/BlazoreDx-Screnshoot/01-BlazoreDx-Login-Eng.png) <br/>

**2.Page Example**
![Page Example](https://raw.githubusercontent.com/idrissanda/BlazoreDx/refs/heads/main/BlazoreDx-Screnshoot/05-BlazoreDx-Example-Form2.png) <br/>

**3.User Management**
![User Manager](https://raw.githubusercontent.com/idrissanda/BlazoreDx/refs/heads/main/BlazoreDx-Screnshoot/04-BlazoreDx-user-management-Eng.png) <br/>

**4.Grid Options**
![Grid Options](https://raw.githubusercontent.com/idrissanda/BlazoreDx/refs/heads/main/BlazoreDx-Screnshoot/06-BlazoreDx-Grid-Options.png) <br/>

**5.Localization Examples**
![Localization Examples-Form](https://raw.githubusercontent.com/idrissanda/BlazoreDx/refs/heads/main/BlazoreDx-Screnshoot/05-BlazoreDx-Example-Form2-TR.png) <br/>
![Localization Examples-Grid](https://raw.githubusercontent.com/idrissanda/BlazoreDx/refs/heads/main/BlazoreDx-Screnshoot/07-BlazoreDx-Localization.png) <br/>

