# User Interface Specification

Create form to Add New User and list Avaible Users

## Tables
- Users
- UserRoles
## _Fields for **Users** Table_
- ID : Auto Increment
- User Name: Text; 30 Char
- Display Name: Text; 100 Char
- Phone: Text; 10 Char
- Email: Text; 100 Char
- RoleID; tinyint;
- State; Bit

## _Fields for **UserRoles** Table_
- RoleID: tinyint
- RoleName: Text; 10 Char

| Role Names |
| ------ |
| Guest |
| Admin |
| Superadmin |


# List Users Form Design
| Object | Object Type |
| ----- | ---------- |
| Users | Grid View |
| New User | Button |
| Hide Disabled User | CheckBox |

# New User Form Design

| Label | Input Type |
| ----- | ---------- |
| Username | InputBox |
| Display Name | InputBox |
| Phone | InputBox |
| Email | InputBox |
| User Role | ComboBox |
| Enable | CheckBox |
| Save | Button |


# License

İzmir Yılmaz