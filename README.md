# Web Application - Koi Feng Shui Consulting System

## Overview

A comprehensive web application designed to provide feng shui consulting services specifically focused on Koi fish ponds. The system helps users determine the most auspicious combinations of koi fish, pond shapes, and directions based on their personal feng shui elements.

## Architecture

### Backend (.NET 6.0)

The backend follows an N-layer architecture pattern:

- **API Layer** (KoiFengShui.BE)
  - RESTful API endpoints
  - JWT Authentication
  - Request handling and validation
- **Service Layer** (FengShuiKoi_Services)
  - Business logic implementation
  - Data processing and calculations
- **Repository Layer** (FengShuiKoi_Repository)
  - Data access abstraction
  - Repository pattern implementation
- **Data Access Layer** (FengShuiKoi_DAO)
  - Database operations
  - Entity Framework Core implementation
- **Business Objects** (FengShuiKoi_BO)
  - Domain models and DTOs

### Frontend (React.js)

- Modern React with hooks
- State management
- Responsive UI components
- API integration

## Key Features

1. **Personal Feng Shui Analysis**

   - Birth date element calculation
   - Life palace determination
   - Compatibility calculations

2. **Koi Fish Consulting**

   - Fish type recommendations
   - Color compatibility analysis
   - Quantity recommendations based on personal elements

3. **Pond Design Guidance**

   - Shape recommendations
   - Directional alignment
   - Size calculations

4. **Advertisement Management**

   - Ad posting system
   - Package management
   - Payment integration

5. **User Management**
   - Authentication & Authorization
   - Profile management
   - Role-based access control

## Technical Features

- JWT-based authentication
- Email notifications
- Payment gateway integration
- Lunar calendar calculations
- Complex compatibility algorithms
- Admin dashboard with analytics

## Prerequisites

- .NET 6.0 SDK
- SQL Server
- Node.js
- npm/yarn

## Getting Started

### Backend Setup

1. Clone the repository
2. Open the solution in Visual Studio
3. Update the connection string in `appsettings.json`
4. Run the following commands:
   bash
   dotnet restore
   dotnet build
   dotnet run

### Frontend Setup

1. Navigate to the frontend directory
2. Install dependencies:
   bash
   npm install

3. Start the development server:

bash
npm start
