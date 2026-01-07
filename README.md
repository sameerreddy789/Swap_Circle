# SwapCircle - A Modern Bartering Platform

This is a Next.js web application built with Firebase that allows users to swap items with others in their community. It provides a modern, secure, and user-friendly platform for bartering goods.

## Core Features

### Modern User Interface & Navigation
- **Dynamic Homepage**: An engaging, animated dotted WebGL background on the homepage creates a visually appealing entry point.
- **Animated Login & Signup**: A fun, interactive login and signup page with animated characters that react to user input.
- **Responsive Mobile-First Navigation**: A modern, interactive bottom menu for seamless navigation on mobile devices, which intelligently hides on scroll.
- **Real-time Notifications**: A notification system in the header alerts users to new trade requests and messages, with a real-time unread count.
- **Holographic & Glassmorphic UI**: A futuristic theme featuring holographic cards, glassmorphic containers, and subtle animated effects for a high-end feel.
- **Dark & Light Mode**: A sleek, high-contrast theme that supports both light and dark modes, and is WCAG-compliant for accessibility.

### Swapping & Trading
- **List Items**: Users can easily list items they want to trade, including details like name, category, condition, description, photos, and location.
- **Advanced Browsing & Filtering**: A comprehensive browse page where users can search, filter by category, condition, location, and swap type, and sort items by newest, user rating, or swap count.
- **Wishlist / Saved Items**: Users can save items to a personal wishlist and easily view them later from their "My Items" page.
- **Propose Trades**: Initiate a trade by selecting one of your items to offer in exchange for another user's item, with an optional introductory message.
- **In-App Messaging**: Once a trade is accepted, users can communicate through a secure, real-time chat to arrange the swap.
- **Temporary Swaps**: In addition to permanent trades, users can propose temporary swaps with a specified loan duration, which are tracked with a countdown timer in the chat.

### User & Profile Management
- **Secure Authentication**: Users can sign up and log in using email/password or Google authentication.
- **Mandatory Consent**: A mandatory consent checkbox on the sign-up page ensures all new users agree to the Terms & Conditions and Privacy Policy.
- **Editable User Profiles**: Users can manage their own public-facing profiles, updating their username, bio, and profile picture.
- **Personal Dashboard**: A "My Items" section where users can manage their own listed items (including deletion) and view items they've saved to their wishlist.

### Safety & Trust
- **Report and Block**: Users can report inappropriate behavior or block other users directly from the chat interface, preventing further communication.
- **Review System**: After a trade is completed, users can leave a rating and review for each other, building a trustworthy community.
- **Secure by Design**: Firestore Security Rules are in place to protect user data, ensuring users can only read and modify their own trades, profiles, and notifications.
