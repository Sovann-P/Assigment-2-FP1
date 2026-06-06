# CRM System Proposal

## Functional Modules

The following modules should be included in the CRM system:

- Contacts
- Account Management
- Leads
- Email and Communication
- Tasks
- Reports and Analytics
- User, Role and Settings Management
- Activity Log
- Opportunities

---

## Database Tables Required

| Table | Purpose |
|---|---|
| `users` | Stores user accounts and credentials |
| `roles` | Defines roles and their associated permissions |
| `contacts` | Stores individual customer and prospect records |
| `accounts` | Stores company and organisation records |
| `leads` | Tracks potential customers and their statuses |
| `opportunities` | Tracks deals, values, and pipeline stages |
| `activities` | Logs all interactions such as calls, meetings, and notes |
| `emails` | Records sent emails and links them to contacts |
| `tags` | Stores labels that can be applied to contacts for segmentation |

---

## Libraries That Can Boost Development

### PHPMailer
PHPMailer is a good library that could boost development. This library can help power the Email and communications module by sending individual and bulk emails to contacts. It also handles attachments and has built in error handling.

### Chart.js
Chart.js is also a great library to help boost development. Chart.js can power the entire reports and analytics dashboard module. They are also fully animated and interactive.

### Medoo
Medoo is also a good library for the backend. It has built-in SQL injection prevention and also replaces raw SQL with readable PHP method calls. It handles Select, insert, delete, update, and join with minimal code.

---

## Security Considerations

### Authentication
Authentication is an important consideration because it verifies who a user is. There are many different strategies for authentication such as multi factor authentication.

### Authorization
Authorization is also important because it controls what an authenticated user can be able to do. We could use role-based access control for this as a strategy as well as principle of least privileged which means the users receive only the minimum access necessary for their job functions.

### Password Security
For password security, we could implement different password policies such as having a character amounts, requiring symbols, and requiring numbers.

### SQL Injection Prevention
SQL injection prevention is also important. SQL injection lets attackers inject harmful SQL code into database queries which may be able to give them access to sensitive data. One way to combat this could be to enable database logging and web application firewall protection.

### Cross-Site Scripting (XSS)
XSS happens when an application displays unvalidated user input on a page. This allows attackers to inject malicious scripts into the browser of anyone who visits it. We can utilize Content security policy headers. This restricts the sources of content that can be loaded which acts as a second line of defense.

### Data Privacy
Data privacy is extremely important because CRMs stores personally identifiable information such as names, emails, phone numbers, etc. A strategy to use for this would be encryption to encrypt sensitive fields in the database.

---

## MVP Proposal — Version 1

A small CRM that could be designed is one that could help a business keep track of just customers, leads, and follow up tasks. This could be a small sales business, for example. Version 1 could have a few different features.

### V1 Features

**Login System**
One feature would be a login system which contains a username and password for logging in.

**Contact Management**
Another feature could be contact management which does a few things like adding, editing, deleting, and viewing customers.

**Lead Tracking**
Another feature would be lead tracking which tracks potential customers and their statuses.

**Task Management**
A task feature could create follow-up tasks for calls, meetings, emails, etc.

**Basic Reports**
There can also be basic reports which counts leads by status or show upcoming tasks.
