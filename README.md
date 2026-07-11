# hotel-access-hub
Single platform that can be installed in computer/system in hotel premises, which allows the staffs to access all the OTA partner's extranet without sharing password with hotel staff

## 1. Problem Statement

You own a small to medium scale hotel/Bed & Breakfast/homestay/guesthouse.

Your hotel staff need access to multiple OTA extranets every day.

Examples include:
      Booking.com
      Agoda (YCS)
      Expedia
      Ingo-MMT
      Airbnb
      Yatra

Currently, everyone knows the usernames and passwords.

This creates several problems:
- Staff can log in from anywhere.
- Passwords can be shared/ compromised.
- Anyone can change the password.
- Passwords are difficult to rotate.
- No record exists of who accessed which OTA.
- You cannot determine which computer was used.
- There is no audit trail.
- If a staff member leaves, you must change every OTA password.

You want a secure solution where:
- Only you can change the password from an admin portal.
- Staff never know OTA passwords.
- Only authorized staff can access specific portals.
- Every access is recorded.
- You can monitor usage remotely.

## 2. Objective

Develop a Windows desktop application called **Hotel Access Hub**

The application becomes the single entry point for all OTA extranets.

Instead of opening Chrome and entering passwords, staff will:

                                Open Hotel Access Hub
                                
                                    ↓
                                
                                Login with their credentials
                                
                                    ↓
                                
                                Select an extranet portal (eg. Click Booking.com)
                                
                                    ↓
                                
                                Booking.com extranet opens automatically
                                
                                    ↓
                                
                                They perform their activities

The passwords remain hidden.

## 3. Scope (Version 1)

This application is built only for one hotel.

          No cloud.
          
          No subscription.
          
          No SaaS.
          
          No multiple hotels.
          
          No public users.
          
          Only your hotel staff.


## 4. Users
  User	                Responsibilities
  Admin	                Complete control
  Manager	              Most portals
  Reception	            Daily OTA operations
  Reservation Executive	Reservations

Maximum:

10 users
