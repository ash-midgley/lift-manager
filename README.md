﻿# Lift Manager

## Setup
- Connect to localhost in Sql Server Management Studio
- Create new Database named LiftManager with default settings
- Add new login with username 'liftmanager' and password 'Password1!'
- Add user mapping to LiftManager Database with db_owner priveleges
- Open solution in Visual Studio
- Open Package Manager Console prompt in Visual Studio
- In project drop down select 'LiftManager'
- Type command `Update-Database` then press enter
- You should see a full list of migrations running against your newly created Database

Once setup complete, run the application using IISExpress in Visual Studio.

Happy lifting meatheads!
