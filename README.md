# RackWatch

# Smart Inventory & Expiry Management System

## Overview
A multi-tenant inventory and sales management system for warehouses, supermarkets, and pharmacies.  
This system tracks stock levels, product expiry, sales, and loans/credit history for customers. It provides async alerts, caching, and analytics dashboards, similar to modern enterprise inventory systems.

## Features
- Multi-tenant management for multiple shops  
- Product CRUD with units (gm/ml/unit), buying cost, and selling cost  
- Auto-suggestions for frequently used products  
- Sales recording with loan/credit tracking  
- Async alerts for low-stock and near-expiry items (Kafka)  
- Redis caching for frequently accessed products  
- Analytics dashboard: 1 week, 4 week, 3 month, 6 month, 12 month sales  
- Role-based JWT security: Admin, Warehouse Manager, Shopkeeper  
- REST APIs for integration with frontend (React optional)  

## Tech Stack
- Backend: Java 21, Spring Boot, Spring MVC, Spring Data JPA  
- Security: JWT, Spring Security  
- Async Messaging: Kafka  
- Caching: Redis  
- Build: Maven  
- Testing: Mockito  
- Frontend (Optional): React  

## Database
- Tenant, Product, Customer, Sale, SaleItem, LoanHistory, Alerts  

## Getting Started
1. Clone the repo  
2. Configure DB and Kafka  
3. Run Spring Boot application  
4. Use Postman or React frontend to test features  
5. View dashboard and alerts  

## Future Enhancements
- Multi-location warehouses  
- Barcode scanner integration  
- Mobile app for shopkeepers  
- Export reports as PDF/Excel
