# RentalApp

**Objective**: A web application for small real estate rental firms that allows leasees to fufill rent obligations and file maintanence requests, allows guests to review and apply for available listings, and administrators to manage propererties, rents, and applications.

# MVP

### Pages
- Home Page
- Login/Signup Page
- Profile Page
- Listings Page
- Payment Page (Third party)
- Administrator Console
- Maintainence Requests

---

### Home Page
- Displays link to **Login/Sign Up Page** (if not logged in).
- Displays link to **Profile Page** (if logged in).
- Displays link to view **Listings Page**.
- Displays link to **Maintainence Requests**.
- Displays link to **Administrator Console** (if logged in and admin authority).

---

### Login/Signup Page
- If logged in, redirect to **Home Page**
- "Forgot Password"
- Login via email address and password.
- Signup, requring email validation, first and last name, password.

---

### Profile Page
If logged in as leasee:
- Display information on current address and lease.
- Display due balances and link to pay, if applicable.

If logged in as guest:
- View application progress, if applicable.

---

### Listing Page
- Map featuring available listings

---

### Payment Page
- Reliance on third party for finanical security (TBD);

---

### Administrator Console
- View all real estate, rented and available.
- Create new or delete current properties.
- Manually modify details of properties such as level of rent, current leasee, pictures, availability status.
- View unresolved maintenance requests.

---

### Maintenance Requests
- Redirect to **Home Page** if not logged in or not leasee.
- Ability to submit maintainence request form for current residence, requires urgency level, subject, description of the request, desired contact info.
