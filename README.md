## Flask Application Design for Rainwater Harvesting System MVP

### HTML Files

#### index.html

- Homepage of the website, providing an overview of the rainwater harvesting system and its benefits.
- Contains a form for users to enter their contact information and address to request a consultation or order the system.

#### contact.html

- Contact page with information on how users can get in touch with the company for inquiries or support.
- Includes an email address, phone number, and a contact form for users to submit messages.

#### dashboard.html

- User dashboard that allows registered users to monitor their system's performance and water usage.
- Displays real-time water levels, system health, and water savings data.

### Routes

#### /

- Main route that renders the `index.html` homepage.

#### /request-consultation

- Route that handles the form submission from the homepage.
- Collects user information and creates a lead for the sales team.

#### /contact

- Route that renders the `contact.html` page.

#### /login

- Route for user login, authenticating users to access the dashboard.

#### /dashboard

- Route that renders the `dashboard.html` page for authorized users.
- Displays personalized data based on the user's connected system.

#### /api/data

- API route that provides real-time data for the user's rainwater harvesting system.
- Used to populate the dashboard with up-to-date information.