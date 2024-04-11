# Software Development Project Name

## Overview

The project is my capstone project for CODE:You. The application manages the service records and parts inventory for an automotive shop. The goal of the project is to demonstrate a general knowledge of C#, Object Oriented Programming principals, and general software development concepts.

## Database

All data for the system including inventory, part types, service history, and vehicle information will be stored in a SQL database named DatabaseName.

## Getting Started

To run this project, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/your-project.git`
1. Update packages
1. Set the following configurations
     * `DatabaseConnectionString` = {server name}/{database name}
     * `ApiBaseUrl` = {api_url}/api/root
     * `SomeOtherConfig` = 42
1. Setup database by running such-and-such on the command line.
1. Run the script located (here) to seed the data in the database

## Admin Setup
1. Register a new user as the admin
1. Create the home location and set the address
1. Create a user in the `ShopManager` role
1. Sign in as the Shop Manager and verify you can see the inventory list under the "Parts Inventory" menu
   

## Dependencies

1. NodaTime - Nuget package for handling time zones
1. AutoPartsDataSolutions API - Catalog of manufacturers and auto parts
