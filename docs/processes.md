# SafeCabinet
## Main User Processes

## 1. Purpose of the Document

The purpose of this document is to describe the main user processes in the SafeCabinet application. It extends the product brief and focuses on how the user interacts with the application in everyday scenarios.

## 2. Scope

This document describes the most important processes related to:
- user registration and login,
- creating and organizing a care space,
- managing dependents,
- adding medicines to the home medicine cabinet,
- planning and recording doses,
- monitoring safety and stock levels,
- accessing public data about medicinal products.

This document does not describe implementation details or technical architecture.

## 3. Main Actors
image.png

### User
The general system user. Depending on the context, they may act as:
- a care space owner,
- a caregiver,
- a patient managing their own medicines.

### Administrator
A person managing one or more care spaces. They may act as:
- the owner of a care space,
- a caregiver,
- a user managing their own medicine cabinet.

### Dependent
A person whose medicines are stored, monitored, or administered within a given care space.

### Caregiver
A family member or another person with limited access to a selected care space.

## 4. Processes

### Process 1: Account Registration and Login

image.png

#### Goal
To allow the user to create an account and gain access to the application.

#### Process Description
1. The user opens the application.
2. The user selects the registration option.
3. The user provides basic details, such as an email address and password.
4. The system creates the user account.
5. The user may then log in to the application.
6. After successful authentication, the system grants access to care spaces.

#### Result
The user has an active account and can use the application.

#### Future Direction
In later iterations, the registration and login flow may be extended with:
- email verification via an activation link,
- social login using providers such as Google or Apple,
- passwordless authentication,
- optional multi-factor authentication for increased account security.

### Process 2: Creating a Care Space

image.png

#### Goal
To allow the user to create a separate context for medicines and dependents.

#### Process Description
1. The user logs in to the application.
2. The user selects the option to create a new care space.
3. The user fills in a simple form with basic details, such as:
    - name,
    - color,
    - icon,
    - description.
4. The system creates the care space.
5. The system opens the dashboard for the newly created space.
6. The user can now manage medicines, dependents, and caregivers within that space.

#### Result
An active care space is created and its dedicated dashboard is available to the user.

#### Future Direction
In later iterations, a care space may support additional configuration options, such as:
- privacy or visibility settings,
- default time zone,
- language preferences,
- default caregivers,
- care space templates for different scenarios,
- notes or goals describing the context of the space,
- archiving or closing a care space,
- reference attachments such as documents or package photos.