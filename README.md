Spotify API Testing – **Project Overview**
This project demonstrates API testing performed on several endpoints of the Spotify Web API using Postman. The testing focused on validating the functionality, reliability, and performance of various Spotify services, including authentication, user profile retrieval, playlist management, and track search.

 **Key Features Tested:**
Authentication & Authorization

Implemented OAuth 2.0 flow to obtain access tokens.

Validated access and refresh token responses and expiry behavior.

User Profile Endpoint

Retrieved current user's profile information.

Verified status codes, headers, and response structure.

Search Tracks & Artists

Tested query parameters with multiple keywords and filters.

Validated pagination, response time, and edge cases.

Playlist Management

Created and updated user playlists.

Added and removed tracks to/from playlists.

Checked response validation and status codes.

Error Handling

Simulated negative test cases (invalid token, wrong endpoint).

Verified correct 4xx/5xx responses and error messages.

**Tools Used:**
Postman for sending requests and organizing test cases

Spotify Developer Console for generating access tokens

JSON Validator to check response structures
