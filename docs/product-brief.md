# SafeCabinet
## Product Brief: Household Medication Safety & Care Workspace

## 1. Product Description

**SafeCabinet** is a web application designed to support patients and 
their caregivers in the day-to-day organization and safety of medication 
use across one or multiple care contexts, such as their own household, 
child care, or care for older adults.

The application supports medication inventory management, dosing schedules,
medication history, safety alerts, and access to public reference data about
medicinal products.

The goal of the application is not to replace a doctor or pharmacist, 
but to increase transparency, safety, and control over the daily management 
of personal treatment and the treatment of dependents.

## 2. Problem

Managing medications in a home environment is a complex and fragmented 
process for many people. This is especially true for patients taking 
multiple medicinal products at the same time and for caregivers supporting 
children, older adults, or other dependents.

Data published by the Ministry of Health and other public institutions 
shows the scale of phenomena such as polypharmacy, fragmented care across 
multiple specialists, and the waste of unused medicines. This points to 
real organizational and safety issues in everyday treatment management.

Information about dosage, stock, and medication safety is often scattered
across packages, notes, phone reminders, caregiver memory, and publicly
available sources of product information. As a result, situations may 
occur in which:

- expired medicines remain in use or storage,
- a medicine runs out without prior warning,
- caregivers struggle to manage medications for more than one person,
- users do not have convenient access to the leaflet, the Summary of Product
Characteristics, or up-to-date product information when needed,
- public notices about recalls or suspensions are not connected to the 
actual contents of the home medicine cabinet.

Consumer solutions available on the market often focus mainly on reminders
to take medication. They less often combine stock management, care for 
multiple people, public registry data, and alerts that support treatment 
safety in a single system.

## 3. Target Users

### Primary Users
- people managing their own home medicine cabinet,
- caregivers supporting parents, grandparents, or other dependents,
- users responsible for medications in more than one care space.

### Secondary Users
- family members with limited access,
- dependents whose data is managed by a caregiver.

## 4. Core Product Value

The application helps the user answer these questions in one place:

- what medicines do we currently have,
- who are they intended for,
- how much is left,
- which of them are close to expiration or already expired,
- what should be taken today,
- whether a given product is covered by a safety notice,
- where to quickly find the leaflet or the Summary of Product 
Characteristics.

## 5. Product Scope

The application focuses on medication management in a non-clinical, 
home, and caregiving context.

The scope includes:
- multiple care spaces managed by one user,
- searching for medicinal products in public registries,
- maintaining a home medicine cabinet with individual packages,
- monitoring expiry dates and stock levels,
- planning doses and recording usage history,
- access to reference documents such as the leaflet and SmPC,
- generating alerts related to safety and treatment organization.

## 6. Out of Scope

The application does **not**:
- diagnose conditions,
- recommend treatment,
- replace a doctor or pharmacist,
- guarantee clinical equivalence of potential alternatives,
- serve as a complete electronic medical record,
- act as a hospital information system,
- handle e-prescriptions or pharmacy ordering in the MVP.

## 7. Key Concepts

### Care Space
A separate context managed by the user, for example:
- My Home,
- Parents,
- Grandparents.

Each care space has its own dependents, medications, schedules, and alerts.

### Reference Product
A medicinal product sourced from a public registry. It represents the 
official reference data for the medicine.

### User-Owned Package
A specific physical package stored in a given care space. It contains 
user-managed data such as:
- remaining quantity,
- expiry date,
- batch number,
- storage location.

### Dependent
A person assigned to a care space for whom medicines are stored or 
administered.

## 8. Main User Flows

### Flow 1: Add a medicine to a care space
1. The user selects a care space.
2. The user searches for a medicine in a public registry.
3. The user selects the correct product.
4. The user adds a physical package with quantity, expiry date, 
and optionally a batch number.
5. The user assigns the package to a dependent or keeps it as general stock.

### Flow 2: Record a dose
1. The user opens today’s dosing plan.
2. The user confirms that a dose was administered or skipped.
3. The system records the event.
4. The system updates history and stock level.

### Flow 3: Safety monitoring
1. The system analyzes stock for expiry dates and quantity thresholds.
2. The system imports public data and notices, if the integration is 
available.
3. The system matches alerts to the user’s products or packages.
4. The user sees organized alerts in the care space dashboard.

## 9. MVP Functional Goals

In the first version, the user should be able to:
- create and manage at least one care space,
- add dependents,
- search for and select a medicine from a public registry,
- add their own medicine package,
- set up a simple dosing schedule,
- record a dose administration or omission,
- receive low-stock and upcoming-expiry alerts,
- open the leaflet or SmPC from the product details view.

## 10. Future Directions

In later versions, the following could be considered:
- integration with product recall and suspension notices,
- searching for potential alternatives,
- integration with reimbursement lists,
- sharing a care space with other caregivers,
- adherence analytics,
- support for planning purchases or replenishment.

## 11. Assumptions and Risks

### Assumptions
- public registries provide sufficiently structured data for product search,
- users are willing to manually maintain data about their own packages,
- a care space is a meaningful organizational unit for people managing 
medications.

### Risks
- public data sources may be inconsistent or incomplete,
- matching safety notices to physical packages may be ambiguous,
- users may misinterpret informational features as medical advice,
- an overly broad scope may weaken the product’s core value.

## 12. Success Criteria for the First Version

The first version of the product will be considered successful if a 
caregiver is able to:
1. create a care space,
2. add a dependent,
3. search for a medicinal product and add its package to the 
medicine cabinet,
4. set up a simple dosing plan,
5. record a dose administration,
6. identify expired medicines or medicines with low stock,
7. open the official leaflet or SmPC without leaving the application context.

## 13. Product Positioning

The product is positioned as a tool for patients and caregivers to manage 
medications more safely in a home setting.

It is not merely a medication reminder app or a clinical system. Its 
differentiator is the combination of:
- home medicine cabinet management,
- separation of data into care spaces,
- use of public medication data,
- and an alert layer that supports treatment safety.