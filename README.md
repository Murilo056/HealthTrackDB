# HealthTrackDB

This repository contains the SQL script to create and configure a database related to tracking health and physical activity information. The database is designed to store user data, physical activities, nutrition categories, and health-related information.

## Database Structure

The database includes the following tables:

- `Usuario`: Stores user information.
- `Attfisica`: List of available physical activities.
- `Alimentacao`: Categories of nutrition.
- `alimen`: Examples of foods for each category.
- `NutricionistasParcas`: Information about partner nutritionists.
- `UsuarioAtividade`: Relationship between users and physical activities.
- `UsuarioAlimentacao`: Relationship between users and nutrition categories.
- `Peso`, `Altura`, `PressaoArterial`: Records of health measurements.

## Procedures and Views

- `TelefoneSP`: Stored procedure to retrieve phone numbers of nutritionists with area code "(11)".
- `Dietaa`: View that combines nutrition information and examples of proteins.

## Example Queries

- Queries for users, health measurements, and relationships.
- Execution of the `TelefoneSP` stored procedure.
- Utilizing the `Dietaa` view.

## How to Use

1. Execute the SQL scripts in Microsoft SQL Server Management Studio or your preferred tool.
2. Ensure you have proper backups before performing operations that may affect the database.

## Contribution

Feel free to contribute, report issues, or propose improvements. Please be respectful and adhere to the code of conduct when interacting with other contributors.
