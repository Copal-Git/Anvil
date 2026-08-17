<center>
<img src='assets/Kayna.svg' width=120px height=120px>

# Kayna
</center>


## Project Overview
Kayna is an open-source retail store management system that serves small businesses with tracking and monitoring their goods including the management of their employees on premises.

Said businesses struggle with staying up to date with their different products' quantities, expiration dates, and placements across their stores and inventories. They still depend on paper-based management which can be prone to human error and is really slow.

Kayna proposes a digital solution to aid employees with an interface to efficiently interact with the store's system, albeit to scan products for metadata or manage the finances of the business.

## Tech Stack

| Component | Tech |
| --- | --- |
| Frontend | React |
| Backend | NestJS |
| Database | PostgreSQL |

 ### Additional Tools:

**Docker** for app containerisation <br>
**NodeJS** for typescript runtime environment <br>
**Electron** for placing the webapp in a desktop wrapper <br>
**InnoSetup** for adding a layer of licensing and agreements on top of the app

## Features

### Feature 1 : User Management
The product owner (admin) shall install a copy of the software on a personal machine which will serve as the source of truth, ie: storing the database and opening up as a server to which the employees connect to in the business' local network.

The admin can assign employees as: <br>
1. managers : have access to product inventory and data
2. cashiers : have access to the mobile version to scan products and obtain information for pricing.

Assigning user accounts ensures a role based system with separated privileges.

### Feature 2 : Product Management

The admin shall be able to add a product, which resembles a unique profile for a certain good.

The admin/manager shall be able to add stock of said product, a stock is a physical instance of a product.

### Feature 3 : Sales Records

Each time a purchase is performed, the items bought are stored in an individual record, the records in mass are called sales, which the manager/admin can view to understand association rules.

### Feature 4 : Data Analytics

Analytics allow the admin/manager to observe the quantities and percentages of a volume in the store, in addition to observing customer traffic through out the week.

### Feature 5 : RAG + Automation Agent ( ? )

## Installation
void

## Folder Structure
void

## Architecture
void

## License
void