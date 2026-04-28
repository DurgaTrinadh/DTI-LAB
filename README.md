📄 Campus Lost & Found Portal (DTI Lab Project)


---

📌 1. Project Title

Campus Lost & Found Portal


---

📌 2. Objective

The objective of this project is to design and develop a web-based lost and found system that helps students report lost items, browse found items, and reconnect with their belongings efficiently within a campus environment.


---

📌 3. Project Description

This project is a frontend-based web application that provides a simple and effective platform for managing lost and found items on campus.

Users can:

Report lost items

View items that have been found

Track item status (lost / found / returned)

Contact item owners using email integration


The application is designed with a clean UI and easy navigation, making it accessible for all students.


---

📌 4. Technologies Used

HTML5 – Structure of web pages

CSS3 – Styling and layout design

JavaScript (Vanilla JS) – Functionality and interactivity

EmailJS – Sending notifications/contact messages

LocalStorage (optional) – Store item data



---

📌 5. System Requirements

🔹 Hardware Requirements

Computer / Laptop

Minimum 4GB RAM


🔹 Software Requirements

Web Browser (Chrome, Edge, etc.)

Code Editor (VS Code recommended)

Internet connection (for EmailJS)



---

📌 6. Modules / Features

🔹 1. Home Page

Displays portal introduction

Shows statistics:

Items Posted

Reunited Items

Still Lost




---

🔹 2. Report Lost Item Module

Form to submit lost item details

Fields like:

Item name

Category

Description

Contact details




---

🔹 3. Lost Items Display Module

Shows all posted lost items

Displays message if no items available

Organized layout



---

🔹 4. Category Filter Module

Filter items based on:

Electronics

Bags

ID/Cards

Clothing

Other




---

🔹 5. Contact / Notification Module

Uses EmailJS to send messages

Helps connect finder and owner



---

🔹 6. Statistics Module

Displays:

Total items posted

Reunited items

Items still lost




---

📌 7. Algorithm / Working Logic

1. User opens the portal


2. Views dashboard and existing lost items


3. Clicks “Report Lost Item”


4. Fills form and submits details


5. Data is stored (LocalStorage or displayed dynamically)


6. Item appears in lost items list


7. Users can filter items by category


8. Interested users contact owner via EmailJS


9. Once item is found, status can be updated




---

📌 8. Use Case

Student loses an item → opens portal → posts lost item → another student finds it → contacts owner → item is returned.


---

📌 9. Information 

🏠 1. Home Page Interface

Portal title and introduction

Statistics dashboard


➕ 2. Report Lost Item Form

Input fields for item details


📋 3. Lost Items Listing

Display of all posted items


🔍 4. Category Filtering

Filtering items by type


📭 5. Empty State UI

“No Items Here” message


📧 6. Email Notification System

Contact functionality using EmailJS



---

📌 10. Project Structure

campus-lost-found/
│
├── index.html
├── styles.css
├── script.js
├── README.md
├── DOCUMENTATION.md
├── Lost_Found_Documentation.pdf
├── images/
├── screenshots/


---

📌 11. Advantages

Simple and easy to use

Helps students recover lost items

No backend required

Lightweight application

Organized category system



---

📌 12. Limitations

No database (data not permanent)

No authentication system

Depends on user honesty

Limited scalability



---

📌 13. Future Enhancements

Add login/signup system

Database integration (Firebase / MongoDB)

Image upload for items

Admin panel for verification

Real-time notifications

Mobile app version



---

📌 14. Conclusion

The Campus Lost & Found Portal provides a simple and effective solution for managing lost items within a campus. It demonstrates how frontend technologies can be used to solve real-world problems and can be extended into a full-stack application for large-scale use.


---

📌 15. References

https://developer.mozilla.org/

https://www.w3schools.com/

EmailJS Documentation

HTML, CSS, JavaScript official docs



---

📌 16. Team Members


Ranganadham Durga Trinadh – UI Design & Development

Vipparti Prasanth Kumar – JavaScript Logic

Badiredla Shanmukha Hari Durga Ram – Email Integration

Kintali Thrilochan – Testing
