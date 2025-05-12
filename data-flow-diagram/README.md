# Airbnb Clone - Data Flow Documentation

## DFD Components

### External Entities
1. **Guest**: Initiates booking and review flows
2. **Host**: Manages property data
3. **Payment Gateway**: External payment processor

### Key Processes
1. **User Management**: Handles authentication and profiles
2. **Property Management**: CRUD operations for listings
3. **Booking Engine**: Reservation lifecycle management
4. **Payment Processor**: Transaction handling
5. **Review System**: Rating collection and display

### Data Stores
1. **Users DB**: Stores credentials and profiles
2. **Properties DB**: Contains listing details
3. **Bookings DB**: Manages reservation records
4. **Payments DB**: Financial transaction logs
5. **Reviews DB**: Guest feedback storage

## Flow Examples
1. New Booking:
   Guest → Search → Select Dates → Confirm → Payment → Booking Record

2. Property Listing:
   Host → Add Details → Upload Photos → Set Availability → Publish
