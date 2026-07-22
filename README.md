# ElecMart – End-to-End Supply Chain Analytics Dashboard

## Project Overview

ElecMart is an end-to-end Supply Chain Analytics project developed to simulate the complete operational workflow of an electronics retail business.

The project covers every stage of the supply chain, beginning with supplier procurement and ending with product delivery and customer returns.

All business data is stored in a **MySQL relational database**.

**Power BI** is directly connected to the MySQL database to retrieve and visualize business data through interactive dashboards.

The database is designed using normalized tables connected through primary and foreign key relationships.

The project includes Suppliers, Categories, Brands, Products, Warehouses, Inventory, Customers, Purchase Orders, Purchase Order Items, Customer Orders, Order Items, 
Payments, Delivery Partners, Shipments, and Returns.

These connected tables make it possible to track every product throughout the complete supply chain lifecycle.

## Complete Product Flow

```
Supplier
   ↓
Product
   ↓
Purchase Order
   ↓
Purchase Order Items
   ↓
Warehouse
   ↓
Inventory
   ↓
Customer
   ↓
Customer Order
   ↓
Order Items
   ↓
Payment
   ↓
Shipment
   ↓
Delivered
   ↓
Return (If Applicable)
```

## Executive Dashboard

The Executive Dashboard provides a high-level overview of the overall business performance.

It monitors Total Revenue, Total Orders, Total Customers, Total Profit, Warehouse Value, and Return Rate.

The dashboard also includes revenue trends, customer segmentation, payment method distribution, product performance, and detailed order information.

## Procurement & Supplier Performance Dashboard

This dashboard focuses on supplier management and procurement activities.

It analyzes purchase costs, purchase orders, supplier ratings, lead time, defect rates, supplier-wise purchase value, purchase order status, and supplier performance.

The dashboard helps evaluate procurement efficiency and supplier reliability.

## Inventory & Warehouse Dashboard

This dashboard provides complete visibility into warehouse operations and inventory health.

It monitors inventory value, current stock, reserved stock, damaged stock, warehouse utilization, and low-stock products.

Category-wise inventory distribution, warehouse capacity, and product availability are also included to support inventory management.

## Order Fulfillment & Logistics Dashboard

This dashboard tracks the complete post-order fulfillment process.

It monitors delivered orders, pending orders, average delivery days, return rate, refund amount, and payment success percentage.

Additional visuals include shipment status, delivery partner performance, return reasons, refund trends, payment method distribution, and delivery timelines.

These insights help evaluate logistics efficiency and customer satisfaction.

## Conclusion

ElecMart demonstrates the practical implementation of **MySQL**, **SQL**, **Power BI**, **DAX**, relational database design, and business intelligence reporting.

The project transforms operational supply chain data into meaningful business insights through interactive dashboards and KPI analysis.

It represents a complete end-to-end supply chain analytics solution for data-driven decision making.
