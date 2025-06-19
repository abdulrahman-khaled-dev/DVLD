# DVLD - Driving License Management System 



## Project Description
A Windows Forms application built with C# for managing driver licensing processes. The system handles the complete lifecycle of driver licensing from application to issuance and management.

## Application Type
- **Windows Forms** desktop application
- **Multi-document interface (MDI)** design
- **SQL Server** backend database

## Complete Feature List

### Core License Services
1. New License Issuance
2. License Renewal Service
3. Lost License Replacement 
4. Damaged License Replacement
5. License Release Service
6. International License Issuance
7. Test Retake Service

### License Classes Management
1. Small Historic Motorcycles
2. Large Historic Motorcycles  
3. Personal Vehicles
4. Commercial Vehicles
5. Agricultural Vehicles
6. Medium Buses
7. Trucks/Large Vehicles

### Testing System
1. Vision Test Management
2. Written Test Management
3. Practical Test Management
   - Scheduling
   - Results Recording
   - Retakes Handling

### Person Management
- Add new applicants
- Update personal information
- Search by national number
- View license history
- Photo upload capability

### Application Processing
- New application creation
- Application status tracking (New/Canceled/Completed)
- Application validation
- License issuance workflow

### User Administration
- User accounts management
- Role-based permissions
- Login/logout system
- Activity logging

### System Management
- License classes configuration
- Test types configuration
- System parameters settings
- Application fees management

## Technical Specifications
- **Frontend**: Windows Forms (C#)
- **Backend**: C# Class Library
- **Database**: SQL Server
- **Architecture**: 3-Layer (Presentation/Business/Data)

## Complete Database Tables
- Applications
- ApplicationTypes  
- Countries
- DetainedLicenses
- Drivers
- InternationalLicenses
- LicenseClasses
- Licenses
- LocalDrivingLicenseApp
- People
- TestAppointments
- Tests
- TestTypes
- Users

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/abdulrahman-khaled-dev/DVLD.git

