# web-chat

**Build a Real-Time Chat Web Application with PHP, MySQL, and JavaScript**
Hello, friends! Today, I’ll guide you step-by-step on how to create a dynamic real-time chat web application using PHP, MySQL, and JavaScript. This tutorial is a follow-up to my previous post on developing a Simple Chatbot with PHP, MySQL, and jQuery Ajax, which many of you found helpful. Due to numerous requests for a full-fledged chat app, I’ve decided to create one tailored to your needs.

**What Does This Chat App Offer?**
When you launch the application, the first page you’ll encounter is a signup form. Here, you’ll provide essential details such as your name, email, password, and profile image.

The email field includes validation, ensuring only valid email addresses are accepted.
The image field also supports validation, allowing only image files to be uploaded.
After successfully signing up, you’ll be redirected to the Users Page. Here’s what it offers:

At the top, your profile picture, full name, current status (online/offline), and a logout button are displayed.
Below, a list of other users (who also signed up) is visible, showcasing their profile pictures, names, statuses, and the last message exchanged with you.
You can either select a user directly from the list or search for them by their name to initiate a conversation.

**Chatting Features**
Once you click on a user, you’ll be taken to the Chat Page, where you can:

View the selected user’s profile picture, name, and status (active/offline).
Send and receive messages in real time. Messages appear instantly in both your and the recipient's chatboxes.
Additional functionalities include:

Auto-Scrolling Chatbox: If messages exceed the chatbox height, it automatically scrolls to the most recent message.
Real-Time User Status Updates: The app dynamically updates the status of users. For example, if someone logs out, they’ll immediately appear as “offline.” Similarly, when a user logs back in, their status changes to “active.”
Secure Login: Users can log back in anytime using the credentials they provided during signup.
**Why This Chat App Stands Out?**
User-Centric Interface: The application is designed to be simple, intuitive, and responsive.
Real-Time Messaging: Powered by modern web technologies to ensure seamless communication.
Dynamic Status Tracking: Keeps everyone informed about users' activity in real time.
Scalability: A robust backend with PHP and MySQL ensures the app can scale as the number of users grows.
