![](https://img.shields.io/badge/build-1.0.0+1-brightgreen)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/najeebaslan/meamar-e-commerce">
    <img src="https://firebasestorage.googleapis.com/v0/b/meamarmanager.appspot.com/o/app_logo%2Flogo_without_background.png?alt=media&token=ed4f051a-f23a-4ff5-bd7c-23bcb2225832" alt="Logo" width="80" height="80">
  </a>

<h2 align="center">Meamar</h2>

  <p align="center">
   An application specialized in construction tools
    <br />
    <br />
    <p>      
      <a href='https://play.google.com/store/apps/details?id=najeeb.aslan.meamar&pcampaignid=web_share'>
        <img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png' height="80"/>
      </a>
    </p>
  </p>
</div>

## About The Project
This application is a Construction Tools Marketplace designed to connect users (clients) with tool owners (managers) in the construction industry. The app allows users to browse, search, and interact with various construction tools and posts, while enabling managers to manage and showcase their tools effectively.

# Application Screens:(Screens 25+)
  <td><img src="https://firebasestorage.googleapis.com/v0/b/weddinghallbooking-2ba28.appspot.com/o/protiflio_images%2Fcrotty_website-1.jpg?alt=media&token=b471e55a-46fe-4c9f-b541-9d37a7d909a4" alt="Image 2"></td>
  <td><img src="https://firebasestorage.googleapis.com/v0/b/weddinghallbooking-2ba28.appspot.com/o/protiflio_images%2Fcrotty_website-2.jpg?alt=media&token=d8454c02-b375-4675-aea1-b6fb32a084ad" alt="Image 2"></td>
  <td><img src="https://firebasestorage.googleapis.com/v0/b/weddinghallbooking-2ba28.appspot.com/o/protiflio_images%2Fcrotty_website-3.jpg?alt=media&token=312c4208-28a7-471c-96fd-1114cab16097" alt="Image 2"></td>
<table>
  <tr>
    <td><img src="screenshots/onboarding1.png" alt="Image 2"></td>
    <td><img src="screenshots/onboarding2.png" alt="Image 2"></td>
    <td><img src="screenshots/onboarding3.png" alt="Image 2"></td>
    <td><img src="screenshots/signup.png" alt="Image 2"></td>

  </tr>
</table>

<table>
  <tr>
    <td><img src="screenshots/for_got_password.png" alt="Image 2"></td>
    <td><img src="screenshots/add_image_profile.png" alt="Image 2"></td>
    <td><img src="screenshots/choose_account_type.png" alt="Image 2"></td>
    <td><img src="screenshots/add_phone_number.png" alt="Image 2"></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="screenshots/chat.png" alt="Image 2"></td>
    <td><img src="screenshots/home_bottom.png" alt="Image 2"></td>
    <td><img src="screenshots/home_search.png" alt="Image 2"></td>
    <td><img src="screenshots/home.png" alt="Image 2"></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="screenshots/tool.png" alt="Image 2"></td>
    <td><img src="screenshots/tools_list.png" alt="Image 2"></td>
    <td><img src="screenshots/tool_search.png" alt="Image 2"></td>
    <td><img src="screenshots/tool_feltter.png" alt="Image 2"></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="screenshots/tool_add.png" alt="Image 2"></td>
    <td><img src="screenshots/delete-or-edit-tool.png" alt="Image 2"></td>
    <td><img src="screenshots/details-tools.png" alt="Image 2"></td>
    <td><img src="screenshots/post_view.png" alt="Image 2"></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="screenshots/post_add.png" alt="Image 2"></td>
    <td><img src="screenshots/posts_empty.png" alt="Image 2"></td>
    <td><img src="screenshots/post_filter.png" alt="Image 2"></td>
    <td><img src="screenshots/post_view.png" alt="Image 2"></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="screenshots/profile_view.png" alt="Image 2"></td>
    <td><img src="screenshots/profile_edit.png" alt="Image 2"></td>
    <td><img src="screenshots/show_owner_details.png" alt="Image 2"></td>
    <td><img src="screenshots/delete_account.png" alt="Image 2"></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="screenshots/dark_home.png" alt="Image 2"></td>
    <td><img src="screenshots/dark_tool.png" alt="Image 2"></td>
    <td><img src="screenshots/dark_posts.png" alt="Image 2"></td>
    <td><img src="screenshots/dark_details_tool.png" alt="Image 2"></td>
  </tr>
</table>


# Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Application Structure](#application-structure)
- [Platform Support](#platform-support)
- [Libraries and Tools Used](#⚙️libraries-and-tools-used)
- [Prerequisites](#prerequisites)
- [Installation](#installation)

## ✨ Features
- **User Authentication**: Login via (phone number-email and password-googleAuth-appleAuth).
- **Account Type Selection**: Users can choose between **Client** or **Manager** roles.
- **Manager Features**:
  - Add construction tools to various categories (e.g., carpentry, painting, tiling, electrical tools, gardening tools, etc.).
  - Create and manage posts.
- **Client Features**:
  - Browse construction tools and posts.
  - Like posts.
  - Contact tool owners via WhatsApp.
- **Tool Categories**:
  - Carpentry tools.
  - Painting tools.
  - Plastering tools.
  - Tiling tools.
  - Home cutting tools.
  - Electrical tools.
  - Outdoor gardening tools.
- **Post Interaction**: Clients can like posts but cannot create or modify them.
- **WhatsApp Integration**: Clients can contact tool owners directly via WhatsApp.
- Able to change profile and delete account.
- Search - Filter - Sort Details 🔍.


## Technologies Used
- **Frontend**: Flutter (version: 3.27.0, Channel stable)
- **Backend**: Firebase
- **Database**: Cloud Firestore, Firebase Storage
- **Authentication**: Firebase Authentication (Phone Auth,Email with Password- Google Auth-Apple Auth)

## Application Structure
After a successful build, your application structure should look like this:

```
├── android         - Contains the necessary files to run the application on Android.
├── assets          - Stores all images, fonts, and translations used in the application.
├── ios             - Includes the files required to run the application on iOS.
├── lib             - The core folder for writing the majority of the Dart code.
├── main.dart       - The entry point of the application.
├── core
│   ├── extensions  - Holds commonly used file extensions for enhanced functionality.
│   ├── helper      - Contains commonly used file imports to assist in development.
│   ├── networking  - Includes commonly used imports for networking tasks.
│   ├── router      - Manages commonly used imports for routing within the application.
│   ├── services    - Handles commonly used imports for various services.
│   ├── theme       - Handles theme-related configurations for consistent visual styling.
│   ├── constants   - Stores commonly used constants like asset paths, icons, and default settings.
│   ├── widgets     - Provides commonly used imports for reusable widgets.
├── data
│   ├── models      - Defines data models that represent the structure of data used throughout the app.
│   ├── repositories- Encapsulates data access logic, providing a clean API for data retrieval.
├── features        - Contains the application's feature modules for organized development.
│   ├─── auth feature     - Manages authentication-related functionality.
│   ├─── tools feature    - Handles adding, editing, and displaying construction tools.
│   ├─── posts feature    - Manages creating, displaying, and interacting with posts.
│   ├─── profile feature  - Handles user profile management.
│   ├─── onboarding feature  - Explain the app features.
│   ├─── settings feature - Manages application settings and preferences.
└── app.dart        - The main application file that initializes the app and sets up the entry point.
```

## Platform Support
| Android | iOS |
| :-----: | :-: |
|   ✔️    | ✔️  |

## ⚙️ Libraries and Tools Used
- **[flutter_bloc](https://pub.dev/packages/flutter_bloc)**: State management.
- **[firebase_auth](https://pub.dev/packages/firebase_auth)**: For phone number authentication.
- **[cloud_firestore](https://pub.dev/packages/cloud_firestore)**: For storing tool and post data.
- **[firebase_storage](https://pub.dev/packages/firebase_storage)**: For storing images.
- **[url_launcher](https://pub.dev/packages/url_launcher)**: For launching WhatsApp to contact tool owners.
- **[shared_preferences](https://pub.dev/packages/shared_preferences)**: For storing user preferences.
- **[popover](https://pub.dev/packages/popover)**: For displaying toast messages.
- **[flutter_screenutil](https://pub.dev/packages/flutter_screenutil)**: : A package for responsive design in Flutter apps by adapting screen sizes and layouts.
- **[firebase_ui_firestore](https://pub.dev/packages/firebase_ui_firestore)**: Provides UI components for easy integration of Firebase Firestore with Flutter applications.
- **[fluentui_system_icons](https://pub.dev/packages/fluentui_system_icons)**:  A collection of Fluent Design System icons for modern Flutter application UIs.

## Prerequisites
- Flutter SDK installed (version 3.27.0 or higher).
- Firebase project set up with Firestore and Authentication enabled.
# meamar-e-commerce
