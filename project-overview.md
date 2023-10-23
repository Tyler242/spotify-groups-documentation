# Spotify Groups

Spotify Groups is a reliable alternative to the Spotify App remote group sessions. It allows users to easily start, end, and join listening sessions with their Spotify Premium friends.

## Android App

The Android App that allows you to easily connect with other Android Spotify Groups users.

### Features

- Group session management
- Friend management
- Queue management
- Playback management

[Design Documents](./android-app-design.md)

## Web API (Backend)

The Spotify Groups Web API acts as a session manager for the Android and iOS/Web App. It also acts as a layer of security between the Database and Applications.

### Capabilities

- Read and write Database securely
- Start, end, join, and leave group sessions

## Database

Stores the necessary user and session information for the Mobile and Web apps.

### Tables

- Users
- Friends
- Sessions

## iOS/Web App for Mobile

Allows for iOS or Web users to join users of the Spotify Groups Android App. Users can join sessions they are invited to but cannot start their own.

### Features

- Friend management
- Queue management
