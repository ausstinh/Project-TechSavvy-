# Technical Approach

### Backend
The server-side application is built using .NET Core as an MVC (Model, View, Controller) design in the C# programming language. .NET Core is a free and open-source, managed computer software framework for Windows, Linux, and macOS operating systems. .NET Core provides a connection to PHPMySQL database using a connection string. Using the MVC design, data from the client-side application can be stored into objects and delivered to the MYSQL database or third-party REST API GitHub Jobs. .NET Core is well known and capable to provide many useful methods to communicate with the MYSQL database and allow HTTP requests to send data to GitHub Jobs API. 
### Frontend
The client-side application is built using React along with several common dependencies such as Material-UI for data table design and Axiox for HTTP requests. React components were used throughout the application to construct classes to store data in using by setting states. States were used as conditions for authentication and data transfer in the axios HTTP requests. React uses a virtual DOM; a DOM kept in memory. Any view changes are first reflected to virtual DOM, then an efficient diff algorithm compares the previous and current states of the virtual DOM and calculates the best way to apply these changes.

### Cloud
Azure Cloud and Visual Studio 2019 are owned by Microsoft. Microsoft uses its own service to publish and deploy .NET projects to the cloud through Visual Studio 2019. When deploying a project, the user will be able to create an app service right away for the project to rest on. Azure Cloud provides automate operating system updates to improve the security of the application environment. Azure Cloud Services monitor the health and availability of the applications. The cloud provides MySQL In App which runs a local MySQL instance with the back-end app and shares resources from the App Service plan.

### Diagrams  
#### Physical Architecture
![phyiscal](https://user-images.githubusercontent.com/47186695/113494197-033b6d00-949b-11eb-97d1-ad2c6694d751.PNG)

#### Logical Architecture
![logicalSolution](https://user-images.githubusercontent.com/47186695/113494188-ec951600-949a-11eb-984b-0a8d75a12ce2.PNG)

###  Data Process FlowChart
![SCFlowchart](https://user-images.githubusercontent.com/47186695/113494242-72b15c80-949b-11eb-82fd-cde87bb9316a.png)

###  Additional Design Diagrams
- [Wireframes](https://github.com/ausstinh/Senior-Captsone-Documentation/tree/main/Wireframes)
- [Data Process FlowChart](https://github.com/ausstinh/Senior-Captsone-Documentation/blob/main/SCFlowchart.png)
- [Class UML Diagrams](https://github.com/ausstinh/Senior-Captsone-Documentation/tree/main/ClassDiagram)
- [ER Design](https://github.com/ausstinh/Senior-Captsone-Documentation/blob/main/ER.PNG)

## Next Page
[Risks & Challenges](https://github.com/ausstinh/Project-TechSavvy-/blob/main/RisksAndChallenges.md)
