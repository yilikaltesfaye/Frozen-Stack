# **PatientPath** 🏥

**PatientPath** is a cutting-edge healthcare platform designed to streamline essential processes like patient registration, appointment scheduling, and medical records management. This project demonstrates how to implement advanced features, including complex forms, SMS notifications, and more, using modern web development tools.

---

## 🚀 **Features**

- **Patient Registration:** Effortlessly register and manage patient details.
- **Appointment Scheduling:** Simplify booking and scheduling for patients and healthcare providers.
- **Medical Records Management:** Securely manage and access patient medical histories.
- **SMS Notifications:** Notify patients and staff with timely SMS reminders.
- **Admin Dashboard:** Manage platform settings and view key data with ease.
- **Secure Backend:** Utilize Appwrite and Sentry for a secure and reliable application.

---

## 🌟 **Tech Stack**

- **Frontend:** Next.js
- **Backend:** Appwrite
- **Database:** Appwrite's integrated database
- **Notifications:** SMS integration
- **Error Tracking:** Sentry

---

## 🗂️ **Project Structure**

- **/pages**: Handles the application routes (Home, Registration, Appointments, etc.)
- **/components**: Reusable UI components for better modularity.
- **/styles**: CSS and styling resources.
- **/lib**: Utilities and helper functions (e.g., SMS integration).
- **/api**: API routes for backend operations (e.g., patient data storage).

---

## **Setup & Installation**

1. **Clone the repository**:

   <!-- ```bash -->
   <!-- git clone https://github.com/adrianhajdin/healthcare.git -->
   <!-- cd healthcare   -->
   <!-- ``` -->

2. **Switch to the `web/fullstack/PatientPath` branch**:

   ```bash
   git fetch --all
   git checkout web/fullstack/PatientPath
   ```

3. **Install dependencies**:

   ```bash
   npm install
   ```

4. **Set up environment variables**:  
   Create a `.env.local` file in the root directory and add the following:

   ```env
   NEXT_PUBLIC_APPWRITE_PROJECT_ID=your_appwrite_project_id
   NEXT_PUBLIC_APPWRITE_ENDPOINT=your_appwrite_endpoint
   SENTRY_DSN=your_sentry_dsn
   SMS_API_KEY=your_sms_api_key
   ```

5. **Run the development server**:

   ```bash
   npm run dev
   ```

6. **Build for production**:
   ```bash
   npm run build
   ```

---

With these steps, the installation instructions are tailored for the `web/fullstack/PatientPath` branch.
