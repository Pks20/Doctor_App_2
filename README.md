* Frameworks and language used
  
    * Springboot and java
* Data flow
  1. Controller
     * AdminController
     * DoctorController
     * PatientController
  2. Services
     * AppointmentService
     * DoctorService
     * EmailService
     * PTokenService
     * PasswordEncryptor
     * PatientService
  3. Repository
     * IAppointmentRepo
     * IDoctorRepo
     * IPTokenRepo
     * IPatientRepo
  4. Model
     * Admin
     * Appointment
     * BloodGroup
     * Doctor
     * Patient
     * PatientAuthenticationToken
  5. Database Used
     * MySQL database

* # Project Summary
   In this project we created Doctor-Appointment basic design project and used mysql database to store the data. We create different type of mapping.
  It follows MVC-architecture.In this application, I have also provided some of the validators on the field values and if a user puts invalid details in response,
  it will handle exception and will revert with Http Status code 400 as a BAD_REQUEST. In my model package I have Doctor,Patient and Appointment class which has all its related data.
  Patient can signUp and signIn in application.Patient can book appointment or Cancel Appointment.
