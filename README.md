# Chamundi Die Cast - Employee Management System

A modern employee management system built with Blazor Server for Chamundi Die Cast company.

## 🚀 Features

- **Employee Information Management**: View, add, and delete employee records
- **Real-time Updates**: Interactive Server-side rendering for instant UI updates
- **Employee Search**: Quick employee lookup by Employee ID
- **Comprehensive Employee Details**: Track employee ID, name, role, phone, station, plant, and joining date
- **Status Tracking**: Monitor employee status (Active/Inactive)
- **Responsive Design**: Modern, gradient-based UI with custom styling

## 📋 Prerequisites

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0)
- A modern web browser (Chrome, Edge, Firefox, or Safari)
- Visual Studio 2022 (version 17.12+) or Visual Studio Code with C# Dev Kit

## 🛠️ Technology Stack

- **Framework**: Blazor Server (.NET 10)
- **Language**: C# 14.0
- **Rendering Mode**: Interactive Server
- **UI**: Custom CSS with gradient designs

## 📁 Project Structure

```
├── Components/
│   ├── Layout/
│   │   └── NavMenu.razor
│   ├── Pages/
│   │   ├── Dashboard.razor
│   │   ├── EmployeeInfo.razor
│   │   └── *.razor.css (component-specific styles)
│   └── App.razor
├── wwwroot/
│   ├── emp_logo.png
│   ├── AMIT_logo.png
│   └── ace-micro.png
└── README.md
```

## 🚦 Getting Started

### Installation

1. **Clone the repository** (or navigate to the project directory):
   ```bash
   cd [your-project-directory]
   ```

2. **Restore dependencies**:
   ```bash
   dotnet restore
   ```

3. **Build the project**:
   ```bash
   dotnet build
   ```

4. **Run the application**:
   ```bash
   dotnet run
   ```

5. **Open your browser** and navigate to:
   ```
   https://localhost:[port]
   ```
   (The port number will be displayed in the console output)

## 📖 Usage

### Employee Information Page

Access the employee information page at `/employee-info`:

- **View Employee**: Select an employee ID from the dropdown and click "View"
- **Add New Employee**: Click "+ Add a new employee" to open the form
  - Fill in all required fields (Employee ID, Name, Role, Phone, Station ID, Plant ID, Date of Joining, Password)
  - Click "Add" to save or "Cancel" to discard
- **View All Employees**: Click "View All" to see a complete list of all employees
- **Delete Employee**: Click the trash icon to remove an employee

### Default Employees

The system comes pre-loaded with 5 sample employees:
- A861 - Kare Gowda (Manager)
- A862 - Rajesh Kumar (Operator)
- A863 - Priya Sharma (Supervisor)
- A864 - Suresh Reddy (Technician)
- A865 - Anita Desai (Quality Inspector)

## 🎨 Customization

### Styling

Component-specific styles are located in `.razor.css` files alongside their respective components.

### Data Storage

Currently, employee data is stored in-memory. For production use, consider implementing:
- Entity Framework Core with SQL Server/PostgreSQL
- Azure Cosmos DB
- Any other database provider

## 🔧 Development

### Running in Development Mode

```bash
dotnet watch run
```

This enables hot reload for rapid development.

### Building for Production

```bash
dotnet publish -c Release -o ./publish
```

## Future Enhancements

- [ ] Database integration for persistent storage
- [ ] User authentication and authorization
- [ ] Employee profile pictures
- [ ] Advanced search and filtering
- [ ] Export to Excel/PDF
- [ ] Employee attendance tracking
- [ ] Role-based access control
- [ ] Edit employee functionality
- [ ] Bulk employee import

## Contributing

1. Create a feature branch
2. Make your changes
3. Test thoroughly
4. Submit a pull request

## About

Developed for Chamundi Die Cast in collaboration with AMiT and Ace Micromatic Group.

---

**Version**: 1.0.0  
**Last Updated**: 2024
