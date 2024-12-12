# 1. C4 Diagrams 🚀

### The C4 model for visualising software architecture :- 
![WhatsApp Image 2024-12-12 at 13 41 26](https://github.com/user-attachments/assets/05930cec-ecb9-4329-aed0-22eadbcda75a)


# 1.1 System Context Diagram 

![Screenshot 2024-12-09 135926](https://github.com/user-attachments/assets/175bdf8f-741d-45b8-9f82-9190064a30af)


This diagram illustrates key interactions:  
1. **Users** interact with the app to stream music and manage playlists.  
2. **Admins** use the Admin Panel to moderate content and view analytics.  
3. **External Systems** provide metadata and handle payment processing via APIs.

# 1.2 Container Diagram 

![Screenshot 2024-12-09 142522](https://github.com/user-attachments/assets/4a9097c5-a546-4f34-9131-a1bff9df945f)



This diagram shows different system components and their interactions:  
1. **Mobile App** - Native app for Android and iOS users.  
2. **Web Application** - Frontend for listeners and admins via browsers.  
3. **Backend API** - Handles requests, authentication, and streaming logic.  
4. **Admin Panel** - Interface for admin users to moderate content and analytics.  
5. **Database** - Stores user data, playlists, and analytics.  
6. **Object Storage** - Manages music files, album art, and user images.  
7. **Third-party APIs** - Provides metadata and processes payments.  

# 1.3 Component Diagram 

## 1.3.1 user flow Diagram 🚀
This diagram illustrates the user journey in the Spotify Clone app, highlighting key actions like login, search, playback, and social sharing.


## Key Features:

![spotify_clone_user_flow](https://github.com/user-attachments/assets/de42e19a-532b-4eda-a022-be63ae48149d)

- **Login/Signup Process:** Users can log in or sign up to access the platform.
- **Music Search and Playback:** Search for songs or playlists and play music seamlessly.
- **Playlist Sharing and Commenting:** Users can share playlists, write comments, and interact with shared posts.
- **Decision-Driven Navigation Paths:** Logical decision points guide users through the platform.

## 1.3.2. Spotify App Flow Overview 🚀

![App_Flow_Overview](https://github.com/user-attachments/assets/1094dc9f-48d1-4dac-a535-6c6e2c64739a)

This diagram illustrates the Spotify app's structure, divided into three main sections:

- **Home**: Features music memos, recently played tracks, and personalized suggestions.
- **Search**: Offers top genres, browsing options, and music memo tools.
- **Library**: Manages playlists, artists, albums, podcasts, and downloads.

### New Features:
- **Music Memo** and **Music Memo Editor** are introduced across all sections for enhanced user interaction.





## 1.3.3. Playlist Tagging and Navigation Overview 🚀

This workflow focuses on enhancing playlist organization and tag-based discoverability within the music app:

- **Playlists in Your Library**:
  - Access and manage playlists categorized as named playlists, tagged playlists, or tagged radios (songs tagged by others).
  - Includes sorting options like creation date, last interaction, or name.

- **Tagging Songs**:

- ![Playlist_Tagging_and_Navigation_Overview](https://github.com/user-attachments/assets/f7b5b8f3-eb73-426d-896c-c6afa6405518)

  - Add metadata to songs via a "More Options Menu."
  - Use text input to create new tags or select from existing ones via dropdown/autocomplete.

- **Search for Tags**:
  - Search specific tags (e.g., `#POP`) to find tagged playlists and tagged radios.
  - Results are displayed in carousel or list formats for seamless exploration.


## 1.3.4. Application Navigation Overview 🚀

This document provides an overview of the application's navigation flow and primary components.

## Components:

![Interface_design](https://github.com/user-attachments/assets/1f1e60ee-28bb-4eee-b216-57f5fa6f0d77)

1. **Authentication Screens**:
   - Includes `Login`, `Registration`, and `Password Reset`.

2. **Navigation**:
   - Features `Top Navigation Bar`, `Mobile Navigation`, and `Sidebar`.

3. **Main Application Screens**:
   - Access core features: `Home`, `Browse`, `Search`, `Playlists`, and `Podcast`.

4. **User Profile**:
   - Includes `Listening History`, `Favorite Tracks`, `User Profile`, and `Account Settings`.

5. **Creator Studio**:
   - Tools for creators like `Music Upload`, `Podcast Upload`, and an `Analytics Dashboard`.

6. **UI Components**:
   - Features include `Playlist Management`, `Recommended Tracks`, `Like Button`, and `Play Controls`.
  

# 1.4 Deployment Diagram 🚀

![Dep](https://github.com/user-attachments/assets/0fb22ffd-bcc4-4e52-82ce-cdb765338437)


This diagram highlights the key system components and their interactions:  
1. **User Devices** - Web and Mobile Apps for accessing the platform.  
2. **Web Server** - Includes services like Music Streaming, Playlist Management, User Authentication, Admin Dashboard, and Subscription Management.  
3. **Database Server** - Contains Music Database, User Database, and Subscription Database for managing user data and music content.  
4. **Payment Gateway** - Handles premium subscription payments via the Payment Service.





