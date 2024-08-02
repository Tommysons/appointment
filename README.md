# Appointment

Appointment is an appointment booking application that facilitates scheduling between patients and doctors. The app features two sides: a user side where patients can sign in, fill out forms, and choose a doctor for an appointment, and an admin side where administrators can manage appointment requests. Patients receive SMS notifications about their appointment status.

## Features

- **User Side:**
  - User authentication and sign-in.
  - Form submission for appointment requests.
  - Doctor selection for appointments.
  
- **Admin Side:**
  - Manage appointment requests.
  - Accept or cancel appointments.
  - Send SMS notifications to patients about appointment status.

## Technologies Used

- **Next.js:** A React framework for server-side rendering and building static web applications.
- **React:** A JavaScript library for building user interfaces.
- **Tailwind CSS:** A utility-first CSS framework.
- **Radix UI:** A collection of accessible and customizable React components.
- **React Hook Form:** A library for managing form state and validation in React.
- **Twilio:** A cloud communications platform for sending SMS notifications.
- **Appwrite:** Backend server for handling authentication and database operations.
- **Zod:** A TypeScript-first schema declaration and validation library.

## Getting Started

### Prerequisites

Ensure you have Node.js and npm installed on your machine.

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Tommysons/appointment.git
    cd appointment
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

### Environment Variables

Create a `.env.local` file in the root directory and add your environment variables:
```env
PROJECT_ID=your_project_id
API_KEY=your_api_key
DATABASE_ID=your_database_id
PATIENT_COLLECTION_ID=your_patient_collection_id
DOCTOR_COLLECTION_ID=your_doctor_collection_id
APPOINTMENT_COLLECTION_ID=your_appointment_collection_id
NEXT_PUBLIC_BUCKET_ID=your_public_bucket_id
NEXT_PUBLIC_ENDPOINT=your_public_endpoint

NEXT_PUBLIC_ADMIN_PASSKEY=your_admin_passkey

SENTRY_AUTH_TOKEN=your_sentry_auth_token
